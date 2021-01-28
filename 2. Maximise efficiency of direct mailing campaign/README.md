## Maximize efficiency of direct mailing campaign 

Direct mailings to a company’s potential customers can be a very effective way for them to market a product or a service. However, as we all know, much of this junk mail is really of no interest to the people that receive it. Most of it ends up thrown away, not only wasting the money that the company spent on it, but also filling up landfill waste sites or needing to be recycled.
If the company had a better understanding of who their potential customers were, they would know more accurately who to send it to, so some of this waste and expense could be reduced.

**Objective**  
To predict whether a customer is interested in a caravan insurance policy from other data about the customer. Information about customers consists of 86 variables and includes product usage data and sociodemographic data derived from zip area codes. The data was supplied based on a real world business problem.
The training set contains over 5000 descriptions of customers, including the information of whether or not they have a caravan insurance policy.

**Target:**  
Build a predictive model for the variable V86

**DataFiles:**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Train Data: carvan_train.csv  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Test Data: carvan_test.csv


**Evaluation Criteria:**  
Fbeta score greater than 0.26 (beta =2) for test data predictions.

**Algorithm used:**  
Support Vector Machines Classifier (SVC)

**Performance of this model:**  
Fbeta = 0.495 (beta=2)
