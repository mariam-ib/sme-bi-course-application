# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- [X] Add datasets used to the `datasets/` folder

#### Files

- [X] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [X] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix`

#### Learning Objective

Calculate and analyze LTV to understand how marketing investment should change to maximize LTV

#### Context

LTV is half of the LTV/CAC performance indicator used across marketing and business analytics, particularly in SaaS businesses. Understanding lifetime value (LTV) of customers, and how it may vary by customer segmentations and marketing channels, is important for marketing groups to guide optimization decisions and maximize marketing’s return on investment. LTV/CAC is often used to help guide major allocations of spending (e.g. shifting paid social dollars to paid search dollars) as well as areas of focus for marketing teams (e.g. improving email copy vs. updating visual content for paid social ads).

#### Steps to be executed by the student (max 6)
- Calculate each customer's first purchase date. Think closely about how to define customer and why
- Calculate each customer's age
- Calculate total customer spend
- Calculate LTV assuming each customer has a lifetime of a year. Duplicate the field
- Build a student vs. non-student filter
- Build a visualization using the student filter, landing page type, and/or marketing origin with median and average LTV values

#### Exercise question:
Where should marketing continue to invest (time or money)? Cut investment? Why?

#### End goal:

![image](https://user-images.githubusercontent.com/122172327/211172162-a259ba36-22cb-4b76-9ce0-9cc6ee5d3112.png)
## 2nd VM Exercise

#### Dataset

- [X] Add datasets used to the `datasets/` folder

#### Files

- [X] **Initial**: Add file to the `exercises/`  folder with the name `ex-2-intial.twbx` or `ex-2-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [X] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.twbx` or `ex-2-sol.pbix`

#### Learning Objective

Calculate and analyze churn rates to understand where marketing should spend time employing churn-prevention tactics

#### Context

Acquisition is half of marketing’s typical responsibilities; customer retention is the other. Retention is typically considered easy if the product is of sufficient quality – typical churn rates for good products are single digits. Considering marketing tactics for churn prevention are typically low cost (email, customer discounts, etc.) and can have significant, positive impact on LTV, identifying pockets of customers that churn at high rates is important.

#### Steps to be executed by the student (max 6)

- Calculate each customer's first purchase date. Think closely about how to define customer and why
- Calculate each customer's most reccent purchase date
- Assume a customer has churned if they have not purchased for over 90 days. Identify which customers are within the scope of churn and filter to just those customers
- Build a flag for each customer that is equal to 1 if the customer (within scope) has churned and 0 if the customer has not
- Calculate churn rate
- Build a visualization using the provided customer demographics to identify which customers marketing should target with churn prevention tactics

#### Exercise question:
Where should marketing focus churn prevention tactics? why?

#### End goal:
![image](https://user-images.githubusercontent.com/122172327/211172530-b765f5dc-4a18-4a4f-a7fe-e128711bd3b4.png)


