# School_District_Analysis
Use Python and the Pandas library to analyze school district data

# Overview of the school district analysis:

# Purpose :
  
  Meria and her superviser asked me to replace the Math and Reading scores for Thomas High School with NaNs while keeping the rest of the data intact becouse the student complete CSV file shows evidence of acadamic dihonesty.
  
# Resourse:
Resources/schools_complete.csv , Resources/students_complete.csv
# Software: 
Python 3.7, Anaconda, Jupyter Notebook and basics of the Pandas library.

# Results:
    Becouse of acadamic dishonesty by the ninth grade students of Thomas High School this Analysis was conducted twice.The first trial included the full set of student data and the second one had thier scores replaced with NaN. The dataframe shown below is a summary reperesenting the district after replacing the ninth Graders' scors with NaN.
    ![District_Summary_DataFrame](https://user-images.githubusercontent.com/77947860/150620438-1eb45e38-fef7-4765-ae07-7fa634b208a2.png)

- Replacing the ninth graders' math and reading scores with NaN resulted in the following changes ;
   - the overall passing percentage for Thomas High School fell to 65%
   - the overall passing percentage for Thomas High School fell to 64.9%
   - the Thomas high school has no longer included on the list of top 5 schools
- When the 9th graders' of Thomas High School had their scores alterd from the calculations, the following changes happend;
    - the overall passing percentage of THS decreased by 0.11%
    - the average scores of THS for math and reading increased by 0.06%
    - spending range $630 to $644 per student so, the overall passing percentage decreased by 0.1%
    - unfortunatly; school rankings are unchanged.Thomas High School (THS) is still the 2nd best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders. 
    - ![updated_Metrics_THS](https://user-images.githubusercontent.com/77947860/150621695-946976de-fb97-49d9-97f9-60a7c622a4c2.png)

# The Effects of school budget and school size
  - average scores and passing percentages do not increase as spending per student increase,this shows that there are more relavant factors than funding to decide average student scores.
  ![Spending_ranges](https://user-images.githubusercontent.com/77947860/150623046-d48de682-a269-4859-a752-fc23894a311b.png)

  when considering School size "Large" schools over 2000 students have the lowest average scores and passing percentages.when we see the performace between "small" & "medium" size schools is negligible, this indicates smaller students are perform better and more confidential setting.
  ![School_size](https://user-images.githubusercontent.com/77947860/150623095-288a1023-ff58-4f57-a291-e01dba3b3cdd.png)

# Districe VS. Charter School
  Charter schools are performing better than district schools in this analysis and also charter schools are top five highest overall passing percentage.
  ![School_type](https://user-images.githubusercontent.com/77947860/150623483-3e4c5906-9abd-4585-a010-b98b71a621ec.png)
  
  # Math and reading scores by grade
  
   After all analyzing the average scores for math and reading by grade level for each school , i  found out that a students grade level does not affect their scores as much as the school that they attend. to see detailed breakdown for math scores by grade showing below;
   ![math_score_by_grade](https://user-images.githubusercontent.com/77947860/150624600-2cc0cb44-3d57-4cc1-8672-351a8eef13f0.png)
   
   Reading score by grade;![Reading_score_by_grade](https://user-images.githubusercontent.com/77947860/150624646-482a761d-3d02-4d48-86ec-70d576ce7696.png)
   
 # Summary
Finally , Omitting the 9th grade from Thomas High School is suboptimal issue because a full set of data is ideal for creating the most accurate results, on the other side replacing the grades with NaN caused THS overall passing percentage and average scores are crash due to this THS lost its placement as top five within district. however; after updating the total student to exclude the Thomas High School ninth grades and omitting their scores from the dataset, Thomas High School(THS) regained its high scores and got its position as the second place in the district.

   




