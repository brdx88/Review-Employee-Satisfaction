# Reviewing Employee Satisfaction
Employment is a relationship between two parties, usually based on contract where work is paid for, where one party, which may be a corporation, for profit, not-for-profit organization, co-operative or other entity is the employer and the other is the employee.

## Problems
Company performance is determined based on employee performance. If most of the employees have poor performance, it can be said that the company's performance is also not good. Therefore, the quality of employees needs to be considered. One indicator of seeing the quality of employees is by knowing employee satisfaction while working at the company.
1. What are the factors that make employees feel satisfied?
2. Can employee satisfaction be predicted using Machine Learning to measure employee performance so that it can measure company performance as well?

## Goals
1. Knowing what factors affect employee satisfaction.
2. Predicting employee satisfaction using Machine Learning.



![](https://github.com/brdx88/Review-Employee-Satisfaction/blob/main/deptsatisf.png)

## Conclusion
1. Only Marketing department which dominated by unsatisfied employees.
2. Either PG or UG education level, they are still dominated by satisfied employees.
3. Only 'job level 2' is dominated by unsatisfied employees while 'job level 3' is neutral.
4. It's obvious that employee who has rating 4 and 5 is way dominated by the satisfied employees, while rating 1 and 2 are the most unsatisfied employees with above 50% employees.
5. Onsite doesn't affect employees satifaction.
6. Employees who has 0 rewards tend to more satisfy than the other.
7. Certified or not doesn't affect employees satifaction.
8. Employees who have \$86750 of their salary and \$24076 have the same percentage of satisfaction: 56%. We can strongly say that in this case, salary doesn't affect the employee's satisfaction.
9. The best Machine Learning Model with Support Vector Machine (Classifier) algorithm could predict employee's satisfaction within 0.59 of 1.0 accuracy.

## Recommendation
1. Companies should pay more attention to their employees who work in the Marketing department, especially those with level 2 jobs.
2. Ratings given by the company affect employee satisfaction, therefore companies can add intrapersonal aspects as a rating indicator. So it is not only technical performance that is assessed.
3. Award is very good given but if you want to balance employee satisfaction with performance, it is better if the award is given periodically. This can create social jealousy that affects employee satisfaction.
4. It's not about money and awards, but must be checked again on the work environment and rating indicators.
5. Since the Machine Learning model got 0.59, we consider that employees dataset should be more reliable. For example, the `salary` feature. The salary feature should not be fixed like categorical and you have to be frankly about the whole data.
