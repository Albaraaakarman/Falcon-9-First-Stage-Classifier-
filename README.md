# Falcon-9-First-Stage-Classifier-
SpaceX has launched Falcon-9 rocket on their website, the rocket comes with a great price (62million$), comparing to other manufacturer which their cost nearby(165million$).    The reason for this is that SpaceX can use the first stage of the rocket  again, I want to determine weather SpaceX Falcon 9 First Stage will land successfully or not.

# Data Collection 
The data have been collected from SpaceX API official website.
To prepare the data well, I used some functions to get important features in consist way, like:( Booster Version, Payload Mass, Cores, and Launch Site).
Also, since the ML is classification, I had to convert all object data into a numerical data to prepare it for analysis, I create a new feature columns called Class that represent weather the launch landed or not by (0 & 1). 

# EDA
For EDA , visual plots were very helpful to discover more about the data and the relationships between features. 
I used various plots, such: Line plot , Cat plot, Bar charts, and more..
Also, a new feature has been created ( AVG success rate ), Average Success Rate , to figure out the relationship between several features and landing average success rate.  
I also used SQL queries for EDA.

# Predictive Analysis 
The predictive model was Classification. I’ve used several algorithm such: KNN, SVM, Decision Trees, and Logistic Regression. 
To compare between them, I’ve created a function that draw a confusion matrix to ease the process of analysis. 
Also, Cross-Validation was used using Grid Search to better overcome overfitting and underfitting. 

# Results
<img width="1503" height="834" alt="image" src="https://github.com/user-attachments/assets/e965ae68-8243-4c6b-bb18-fdc5c2abcbbe" />
<img width="690" height="702" alt="image" src="https://github.com/user-attachments/assets/5d115a13-d456-451c-8b66-492c71dc2d02" />
<img width="618" height="687" alt="image" src="https://github.com/user-attachments/assets/9174537e-8203-40f6-b310-6532269f2be3" />
<img width="1069" height="699" alt="image" src="https://github.com/user-attachments/assets/16aaec72-b17a-4bf5-b6ff-9a2af1560177" />
<img width="823" height="696" alt="image" src="https://github.com/user-attachments/assets/8c2c44a9-64e5-474d-ac82-1e4b7d811c6d" />

Most common features affect the results are:
Booster Version, Payload Mass, Launch Site, and Cores. 
Best methods to determine the accuracy of the classification model are: 
            Logistic Regression and SVM with accuracy of 94%




