# Churn Analysis (online school)
Time-series analysis of Churn and Sleeping students, as well as Rehab Students out of all Active students for each particular month. 

## Project

The primary goal of this project was to analyze students' payment histories and lesson visitation patterns over time, enabling me to assess the number of active students, churn rates, and sleeping rates. The analysis provide the foundation for further understanding the reasons why students are leaving the school, with the aim of reducing the rate of student churn.

![Screenshot 2023-04-19 201024](https://user-images.githubusercontent.com/116592259/233165468-2fbac4bc-e8ed-46bb-8898-361bdff86ddf.png)

## Terms and Definitions

* Active students - all students with scheduled lessons for the given month
* Churn students - students with no lessons on the balance (considered as churn students if it's more than 8 days before next payment)
* Sleeping  students - students with positive balance and paused visiting (considered as sleeping students if it's more than 30 days before next lesson)
* Rehab students - students switched back from churn status (Churn Rehab) or sleeping status (Sleeping Rehab)

## Main stages 

The project implementation included the following main stages:

* In this project, I utilized MySQL to query data and obtain information on all student transactions and lesson visits, allowing me to determine the balance of each student. Using this data, I identified students who were either churning, sleeping, or in a state of rehabilitation based on specific conditions. To aid in my analysis, I used Google Colab to write queries and create simple visualizations.

* Next, I transferred my SQL code to Tableau and created a data model that established relationships with other relevant tables. This allowed me to filter data by specific products, lesson types, and other variables.

* Finally, I used Tableau to develop a simple, yet effective, dashboard that displayed time-series visualizations of churn and sleeping students. To ensure that my data was up-to-date, I scheduled incremental data updates. By leveraging these techniques, I was able to gain valuable insights into the churn behavior of online school students.

## Next steps

While the analysis yielded insights into the dynamic of student churn, it did not reveal specific patterns or underlying reasons for churn. To gain a deeper understanding of Students Churn, further analysis needed to examine impact of factors such as course content, teacher effectiveness, student demographics and other. This more in-depth analysis will help to identify potential causes of student churn and suggest ways to reduce it in the future.
