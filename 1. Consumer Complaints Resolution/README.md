## Consumer Complaints Resolution 

Consumer complaint resolution is important to any business. In this particular case we have been given detailed
consumer complaints along with whether consumer disputed with the conclusion.  

**Objective:**  
Predict which consumers are more likely to dispute resolution of a complaint in order to give
more attention as to how their complaints are handled and how persuasively final conclusions are conveyed to them.  

**Target:**  
Build a predictive model for the column “Consumer_disputed".

**Data Files:**  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Train Data: Consumer_Complaints_train.csv  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Test Data:  Consumer_Complaints_test.csv

The training data contained in the file Consumer_Complaints_train.csv is larger than the Github’s limit of 100Mb, so it has been zipped.                                                                                                                                                  

**Evaluation Criteria:**  
AUC score of at least 0.54 for test data predictions.

**Algorithm used:**  
TfidfVectorizer to create features out of the text components of the data followed by a Tuned Random Forest.

**Performance of this model:**  
AUC = 0.64880
