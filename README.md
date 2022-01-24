# School_District_Analysis
## Purpose
   The school board has notified Maria and her supervisor that the student file shows the academic dishonesty, reading and math grades for Thomas High School ninth graders appear to have been altered. So now we need to replace those scores with NaNs while keeping the other data intact. Once those scores are replaced we need to rerun rhe school district analysis. 
### Code Changes:
  
  1. Replacing all the Ninth grader scores in Thomas High School with NaN in student_data data frame
![image](https://user-images.githubusercontent.com/56806834/150752895-e2ced0ca-e0ad-4283-acf7-0a48f93fce29.png)

  2. Calculating total number of students by eliminating ninth graders from Thomas High School
  ![image](https://user-images.githubusercontent.com/56806834/150751014-4f6f219c-fbac-4655-abb8-97dd160d33a6.png)
  
  3. Use this new total to calculate math, reading and overall percentages
  ![image](https://user-images.githubusercontent.com/56806834/150751806-f02ff1c8-3785-41d0-b97b-4400bc750661.png)
  
  4. For Thomas High School Passing Averages and Percentages, only take 10th, 11th and 12th grade student numbers.
  ![image](https://user-images.githubusercontent.com/56806834/150752256-54ecacdc-bb2d-4c17-8448-9efca7014e5c.png)
  
  5. For the DataFrame per_school_summary, replace all the averages and percentages with the new calculated values
  Adding math score replacement as an Example:
  ![image](https://user-images.githubusercontent.com/56806834/150752570-2efec68c-b2cd-4121-8c4a-ed48a6e42a81.png)

   

## Results
 1. District Summary:

   There is a very small change in Average Math score, %Passing Math, %Passing Reading. But there is a big jump in Overall passing.
    
   - District Summary Before:
   ![image](https://user-images.githubusercontent.com/56806834/150744739-afc7fec3-73a0-492a-bce1-13783e1ec551.png)
    

   - District Summary After:
   ![image](https://user-images.githubusercontent.com/56806834/150742920-4f2048d5-4458-4a5b-b69a-5a4dba7b0dc3.png)


 2. School Summary:
 
  Thomas High School has very minimal change in Average Math Score, Average Reading Score, % Passing Math, % Passing Reading and % Overall Passing. Total number of students, total school budget, per student school budget has no change. That is because for scores ninth graders were not counted as total number of students.
  
   - Before Change:
   ![image](https://user-images.githubusercontent.com/56806834/150745176-1445e018-a51c-4487-8618-21513713f78f.png)

   - After change:
   ![image](https://user-images.githubusercontent.com/56806834/150738118-9b6c36ee-e1dd-4a6d-a475-d97a2cff450d.png)

    
 3. Math Scores by Grade:
 
    Changes impacted only Thomas High School. You can see Ninth graders scores are not counted. 
    
   - Before Change:
    ![image](https://user-images.githubusercontent.com/56806834/150745488-2c61cab1-8581-4f1f-b024-58b9b1d4956b.png)

    
   - After Change:
    ![image](https://user-images.githubusercontent.com/56806834/150741441-b61b05be-88f9-43a1-9bc1-9faa04b9eca5.png)

 4. Reading Score by Grade:
 
     Changes impacted only Thomas High School. You can see Ninth graders scores are not counted. 
     
   - Before Change:
    ![image](https://user-images.githubusercontent.com/56806834/150745591-97fdfd02-dc3d-4aba-9071-a33f82e6d474.png)

    
   - After Change:
    ![image](https://user-images.githubusercontent.com/56806834/150741597-e05e73af-b91f-4ffc-89ae-3c4e7b7f493c.png)

 5. Scores by school spending:

      Thomas High School has very minimal change in Average Math Score, Average Reading Score, % Passing Math, % Passing Reading and % Overall Passing. Averages have no impact.
     
   - Before Change:
    ![image](https://user-images.githubusercontent.com/56806834/150745787-adc21c80-32fb-4c9a-b1d7-f8e78cbb99ea.png)
    ![image](https://user-images.githubusercontent.com/56806834/150745881-b2067097-eb92-451b-9f7f-0f123f26c413.png)


    
   - After Change:
   ![image](https://user-images.githubusercontent.com/56806834/150741764-6a799f72-2b13-4652-8f3b-48e6aed59144.png)
   
  ![image](https://user-images.githubusercontent.com/56806834/150742578-34113e86-f847-495e-b9d7-6d5124b7dde3.png)

   
 6. Scores by school size:
 
  Thomas High School has very minimal change in Average Math Score, Average Reading Score, % Passing Math, % Passing Reading and % Overall Passing. Averages have no impact.
   - Before Change:
    ![image](https://user-images.githubusercontent.com/56806834/150746048-764bcbca-5d52-4e0a-8606-898633c299aa.png)
    ![image](https://user-images.githubusercontent.com/56806834/150746114-3931b7da-5d5c-4c14-86aa-d1e0cd55a51c.png)


  
   - After Change:
 ![image](https://user-images.githubusercontent.com/56806834/150742076-b405ade0-4c79-46c1-a2d0-34301b2ed31d.png)
 
 ![image](https://user-images.githubusercontent.com/56806834/150742403-de3fd44d-33c1-4fd2-a289-b69831de8898.png)

 
 7. Scores by school type:

Averages have no impact.

   - Before Change:
   ![image](https://user-images.githubusercontent.com/56806834/150746204-a18f6eb0-4c7a-4a47-9bc0-79fd0ce86f6f.png)

  
   - After Change:
   ![image](https://user-images.githubusercontent.com/56806834/150742495-731e6ea2-0b8a-4776-9a1c-b49a3c92c00b.png)
   
   
## Summary
Student data itself changed to show NaN for Thomas High School Ninthgraders math and reading scores. This changed the way the we counted the total number of students for calculating averages and percentages. Biggest change we saw is the % Overall passing in District summary. That took a big jump from 65% to 90.6%. Average Math scores for District Summary and Thomas High School summary has very small change. Same is true for Average reading score, % math passing, % reading passing. Budget, total number, per capita, school size these have no impact because of the data change that was done.


      
