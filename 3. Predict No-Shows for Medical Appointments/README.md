## Predict No-Shows for Medical Appointments

Resource planning is crucial for any business; it's even more so for operations struggling with resource crunch. Government sponsored medical services is a prime example of such an operation. In almost all developing countries, there is severe shortage of medical personnel and at the same time, not ideal living conditions for big chunk of the population further exacerbates need of medical attention.

Governments have tried floating subsidized access to poor families to increase access to healthcare. One big problem which stops better utilization of this facility is that people make appointments but do not show up without a notice. That time slot could have been given to a needier person if authorities were able to determine who is very likely to not show-up and follow-up appropriately.

The task here is to make use of historical records to build a model for predicting a No-Show for an appointment given appoint details, medical history and demographic details of the customer.

**Objective:**  
To build a predictive model for predicting No-shows given the appointment details. 

**Target:**  
Build a predictive model for the variable ‘No-show’

**Data Files:**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Medical History: medical_history.csv  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Demographic Details: demographic_details.csv  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Train Data: train.csv  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Test Data: test_share.csv

**Evaluation Criteria:**  
roc_auc score >0.66

**Algorithm used:**  
Tuned Random Forest Classifier

**Performance of this model:**  
roc_auc score = 0.7434
