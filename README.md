# Pandas-Challenge
![education](https://github.com/ryodaimatsui/pandas-challenge/assets/137141385/5341fc2d-6e3d-421b-b7d6-175e9443e3d9)

- Executive Summary:
  This analysis takes a look at data from 15 different schools and attempts to evaluate 
  the performance of the schools based on the following data categorizations:
  
      - Highest performing schools based on the overall passing percentage.
      - Loweset performing schools based on the overall passing percentage.
      - Both math and reading scores by grade level.
      - And, math and reading scores based on each each school's spending, size, and school type. 

  The first dataframe titled, 'schools_data_complete,' is produced by merging two datasets, and subsequently, 
  various variables and dataframes are created using this dataframe for the analysis.
 
- Findings:
  Upon analysis of the dataframes that were created, as a whole, charter schools outperformed district schools when
  looking at the average percentage of 'overall passing' — calculated by dividing the number of students that passed 
  BOTH math and reading by the total number of students. In fact, when sorting the schools based on their respective
  'overall passing' rates, the top five schools were charter schools, while the bottom five were district schools.
  
  Additionally, schools that were categorized as small(i.e., less than 1000 students) or medium(i.e. between 1000-2000
  students) considerably outperformed large schools (i.e., 2000-5000 students) in 'overall passing.' Furthermore, 
  and contrary to the assumption that increased spending will increase school performance, schools that spent less
  than 585(USD) and between 585-630(USD) performed better than schools that spent more per student. 
  
