### Project overview
This repo contains solution to my Big Data module coursework project I've completed at the University of Sheffield. 
The main aim of this project was to provide answers to questions from a mock client. Below are the client's questions:
1. Programmatically confirm that all papers have unique IDs and output the number of
papers in the file.
2. What is the average number of authors per paper?
3. How many different journals were the papers published in?
4. Find the 5 authors with the highest number of publications. Give their names along
with the number of publications they contributed to.
5. To gain some additional information about publication quality, you’d like to join the
paper information with the journal information you have. Following this, find the top 5
authors with the highest cummulative impact factor (notice that journals have different
impact factors listed in the journal file in the IF column). Output both the author
information and the cummulative impact factor.
6. You’d like some additional information about publication trends. How many publica2
tions with impact factor > 1 were published in each of the years between 2010-2020?
Ensure that your answer for each year is visible in your report.

The answers to these questions had to be provided using a selected big data solution. I've selected PySpark dataframes as my main 
solution, however I've also provided additional solution to the problem using PySpark SQL. I've also conducted some
additional analysis of the dataset (for questions 1, 2 and 3) which are contained in the Pyspark dataframes solution.
The project had been using Databricks platform to develop the solution.
