# Employee Performance Project

**INX Future Inc**

INX Future Inc , (referred as INX ) , is one of the leading data analytics and automation solutions provider with over 15 years of global business presence. INX is consistently rated as top 20 best employers past 5 years. INX human resource policies are considered as employee friendly and widely perceived as best practices in the industry.

Recent years, the employee performance indexes are not healthy and this is becoming a growing concerns among the top management. There has been increased escalations on service delivery and client satisfaction levels came down by 8 percentage points.

CEO, Mr. Brain, knows the issues but concerned to take any actions in penalizing non-performing employees as this would affect the employee morale of all the employees in general and may further reduce the performance. Also, the market perception best employer and thereby attracting best talents to join the company.

Mr. Brain decided to initiate a data science project , which analyses the current employee data and find the core underlying causes of this performance issues. Mr. Brain, being a data scientist himself, expects the findings of this project will help him to take right course of actions. He also expects a clear indicators of non performing employees, so that any penalization of non-performing employee, if required, may not significantly affect other employee morals.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Major Findings:**

# Low Performance
<ul>
  <li>Sales Department has the maximum no. of low performance employees.</li>
  <li>Sales Executive Role has the lowest ratings.</li>
</ul>

# High Performance
<ul>
  <li>Development Department has maximum no. of high performing employees.</li>
  <li>Developer Role has the highest ratings.</li>
</ul>

<b>Performance Rating</b>
![image](https://user-images.githubusercontent.com/35792446/123276304-ae037a80-d522-11eb-84bf-a72ca2d636a2.png)

<b>Employee Department</b>
![image](https://user-images.githubusercontent.com/35792446/123276341-b52a8880-d522-11eb-8e0c-c378547c53a9.png)


<b>NUMERICAL FEATURES IMPACTING PERFORMACE BASED ON PEARSON CORRELATION COEFFICIENT</b>
Significant Correlation exists between the following features:
<ul>
  <li>YearsWithCurrentManager</li>
  <li>YearsSinceLastPromotion</li>
  <li>TotalWorkExperience</li>
  <li>ExperienceInCurrentRole</li>
  <li>ExperienceAtThisCompany</li>
  <li>Very less Correlation seen with Performance Rating and other variables.</li>
</ul>

<b> Model Performance</b>
<li>XG Boost Classifier performed well and gives an accuracy of 93.39</li>
![image](https://user-images.githubusercontent.com/35792446/123278207-6120a380-d524-11eb-9eec-c6f5864e5de3.png)

<b>Feature Importance</b>
Top 3 feature affecting the Employee Performance:
<ul>
  <li>YearWithCurrManager</li>
  <li>Gender</li>
  <li>EmpWorkLifeBalance</li>
</ul>
![image](https://user-images.githubusercontent.com/35792446/123278469-9927e680-d524-11eb-8604-b1b83764b8c3.png)

<b>Recommendations:</b>
<ol>
<li>Development Department has standout performance so we can recommend Development Department based on their performance to improve more performance.</li>
<li>Sales Executive and Developer Employees have a better performance as compare to other employee so we want to recommend those employees which have a better performance.</li>
<li>In EducationBackground ‘Life Sciences’ educated people have better performance so we recommend only these people to improve employee performance.</li>
<li>BusinessTravelFrequency ‘Travel_Rarely’ employees have the best performance so we want to recommend the Travel_Rarely employees.</li>
<li>Further data to be collected on factors impacting Environment Satisfaction and Work Life Balance with people of Experience less than 3 years.</li>
</ol>









