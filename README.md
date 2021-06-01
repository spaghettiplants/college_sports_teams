# college_sports_teams
First capstone through Thinkful. Hypothesis testing for expenses to revenue ratios for gendered college sports teams.

<details>
  <summary>Intro</summary>
  
  # Doc Overview 📄
  There are 3 documents associated with the 1st iteration of this project. There's the slide deck "Expenses and Revenues of College Sports Teams by Gender",
  a Jupyter Notebook titled "College EtR Ratio Report", and another titled "Overall EtR Ratio Report".
  
  The College EtR Ratio Report (1st version) uses some not-so-stellar coding. There's some ~brute force~ and several inefficient for-loops. The code along with
  another iteration of the project with a slightly different goal will be updated and provided here.
  
  **A 2nd version of this project, with a different hypothesis, is laid out in the third Jupyter notebook, "Overall EtR Ratio Report".**
  
  # Background for Version 1 ✨
  The U.S. Department of Education keeps various records over universities' athletic departments. Gender equity in sports is a commonly discussed topic.
  It's important to consider how we can work to create a more equitable system. As an educational institution, the U.S.     
  Department of Education can gain benefits from seeking to explore the public college system's distribution of finances in a data-driven manner.
  
  The original research question for this project was: How many public 4-year universities do not spend an equitable amount of money on their gendered sport teams?
  
  This question leads us to the following null and alternative hypotheses:
  
  **H0:** On average, public 4-year universities spend the same ratio of funds on women’s teams as men’s teams when normalized by the revenue to
  total revenue ratio that each team brings to the university.
  
  **Ha:** On average, public 4-year universities do not spend the same ratio of funds on women’s teams as men’s teams when normalized by the
  revenue that each team brings to the university.
  
  # Background for Version 2 ✌🏼
  In this iteration, we analyze the Expenses to Revenue ratios of the entire system - that is, we develop the ratios by adding
  the expenses and revenues for all colleges by a year. This leaves us with a set of ratios for each sport by gender. Thus, the new
  research question for this scenario is:
  
  For each year from 2010 to 2018, how many sports have a difference in their expenses to revenue ratio by gender?
  
  The null and alternative hypothesis are as follows:
  
  **H0:** On average, sport teams of public 4-year universities spend the same ratio of funds on men's and women's teams when normalized
  by the ratio of revenue funds.
  
  **Ha:** On average, sport teams of public 4-year universities do not spend the same ratio of funds on men's and women's teams when normalized
  by the ratio of revenue funds.
