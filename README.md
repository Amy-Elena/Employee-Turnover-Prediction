# Employee-Turnover-Prediction
Google Advanced Data Analytics Course; The Capstone Project  

#### Project Overview
This project focuses on predicting employee attrition based on various features such as performance evaluations, number of projects, tenure, and average monthly hours. The goal is to help the company Salifort Motors proactively identify employees at risk of leaving and propose actionable recommendations to improve retention.
Using regression and tree-based models, this project analyzes factors that influence employee attrition. After initial model building, feature engineering was conducted to enhance the model by introducing a binary "overworked" feature and removing features likely to cause data leakage, such as satisfaction level.

#### About the Company
Salifort Motors is a fictional French-based alternative energy vehicle manufacturer. Its global workforce of over 100,000 employees research, design, construct, validate, and distribute electric, solar, algae, and hydrogen-based vehicles. Salifort’s end-to-end vertical integration model has made it a global leader at the intersection of alternative energy and automobiles. 

#### The Business Case
You are a data professional working for Salifort Motors. 

Currently, there is a high rate of turnover among Salifort employees. (Note: In this context, turnover data includes both employees who choose to quit their job and employees who are let go). Salifort’s senior leadership team is concerned about how many employees are leaving the company. Salifort strives to create a corporate culture that supports employee success and professional development. Further, the high turnover rate is costly in the financial sense. Salifort makes a big investment in recruiting, training, and upskilling its employees.

You have received the results of a recent employee survey, and the senior leadership team has tasked you with analyzing the data to come up with ideas for how to increase employee retention. To help with this, they would like you to design a model that predicts whether an employee will leave the company based on their  department, number of projects, average monthly hours, and any other data points you deem helpful. If Salifort could predict whether an employee will leave the company, and discover the reasons behind their departure, they could better understand the problem and develop a solution. 

A good model will help the company increase retention and job satisfaction for current employees, and save money and time training new employees. 

#### Key Insights
* Overwork and Tenure: Employees with a high number of projects, longer working hours, and at least four years of tenure are more likely to leave.
* Evaluation Scores: There seems to be a correlation between hours worked and evaluation score, but working long hours doesn't guarantee a good evaluation score.

#### Feature Importance
Both the decision tree and random forest models identified the following top features:

* Last Evaluation: Key indicator of employee performance and attrition.
* Number of Projects: Higher project load correlates with higher risk of leaving.
* Tenure: Employees with four or more years at the company are at greater risk.
* Overworked: Working more than 175 hours per month increases the likelihood of attrition.

#### Business Recommendations  
Based on the model findings, the following steps are recommended to retain employees:

* Limit Project Load: Set a cap on the number of projects employees can handle to prevent burnout.
* Reward and Promote: Consider promoting employees with at least four years of tenure or investigate why they are more likely to leave.
* Work Hours Flexibility: Offer rewards or incentives for long hours or reduce required working hours.
* Clarify Policies: Ensure that overtime policies and workload expectations are transparent and fair.
* Cultural Shift: Encourage a balanced work culture by re-evaluating the criteria for high evaluation scores, ensuring they aren't reserved for those working excessive hours.

#### Next Steps

* Address Data Leakage: Test model performance without the last_evaluation feature to ensure it doesn't create unrealistic expectations.
* Satisfaction Score: Investigate whether the satisfaction score, if available, might also be a factor in predicting attrition.
* Clustering: Apply a K-means clustering approach to explore potential patterns or groupings within employee data.

#### Ethical Considerations
Care should be taken when using predictive models to avoid unfair treatment of employees. Over-reliance on specific metrics like evaluation scores or workload might inadvertently penalize employees. Recommendations should focus on improving work conditions and supporting employee well-being.  

---
