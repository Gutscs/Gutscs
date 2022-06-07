## Hello there and Welcome! I'm Gustavo Castro :wave:  
 <div align="center">
  <a href="https://github.com/Gutscs">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Gutscs&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
</div>
  
 
## Data Science Projects:
 
### [Rossmann Store - Forecasting Sales](https://github.com/Gutscs/Rossmann-Forecasting-Sales)
  * Rossmann's CFO requested the store managers a prediction of their daily sales for up to six weeks in advance. The CFO wants to renovate each store by using part of the future store's revenue.
  * **Solution:** 
       * A **XGBoost Regressor** model deployed in Heroku with an API that allows the user to get the predictions using a Telegram chat.
       * Model obtained a MAPE of 9.84%, predicting a total revenue of R$285,701,696.00 +/- R$751,154.18 for the next six weeks.
 
 ### [Health Insurance - Cross Sell](https://github.com/Gutscs/Health-Insurance-Cross-Sell)
  * An Insurance company that has provided Health Insurance to its customers wants to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance. But the sales team has a limited number of calls within the campaign period to offer their customers this new insurance.
  * **Solution:** 
       * A **Logistic Regression** model that obtain the probability of a customer being interested in the vehicle insurance, so the sales team can prioritize the ones with a higher probability.
       * Considering 127K new customers with just 12.23% interested customers and a limitation of 20K calls, the model reaches 45.64% (approximately 2.6x more customers than using a random method) of the interested customers and considering 40K calls, it reaches 79.75% (approximately 2.3x more customers than using a random method).
       * The model was deployed in Heroku with an API that allows the user to get the propensity score for each customer using a given google spreadsheet.

 

### [High Value Customers (Insiders) - Clustering](https://github.com/Gutscs/Insiders-Clustering)
  * The marketing team of an E-commerce store wants to identify the high value customers to provide some benefits to maintain their loyalty. Also, it wants to know the main characteristics of this group, to understand their influence on the company's revenue. 
  * **Solution:**
    * A **Hierarchical Clustering** model that groups the customers according to its characteristics, such as: gross revenue, recency days, frequency, quantity of products purchased and quantity of products returned.
    * The obtained cluster Insiders consists of 7 customers (0.12% of the total customers) who contribute with 11.9% ($1,201,978.37) of the company's revenue ($10,096,818.07) in the selected period.
    * The model was deployed using an AWS EC2 Instance running Ubuntu. The input data comes from a S3 Bucket and the output is saved on a PostgreSQL database in the AWS RDS, which can be accessed by the user and used to create dashboards and reports.
 

<div> 
  <a href = "mailto:gutscs@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/gustavo-castro-dos-santos/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 

</div>



