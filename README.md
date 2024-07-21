## Problem Statement
Educational institutions face numerous challenges in trying to maintain a safe environment and effective administrative procedures. Regularly, attendance and identification tracking methods are manual, tedious, prone to errors and cannot offer real-time monitoring. Additionally, conventional access control systems may be vulnerable to hacking or security breaches. For that reason, there is need for an automated solution that will effectively address these issues with respect to school security at large.

## Use Case Diagram 
![image](https://github.com/Girraffeteeth/School-Security-System-Using-Facial-Recognition/assets/91562191/1555c429-846b-4765-8d07-0c98529ccf4e)

## Algorithm Used
1. Haar Cascades - For Face Detection
2. Local Binary Pattern Histograms (LBPH) - For Face Recognition
## Technologies Used
Python, OpenCV

## Domain 
Machine Learning and Computer Vision

## Results
 Receiver Operating Characteristics (ROC) and Area Under Curve (AUC)
   
   ![image](https://github.com/Girraffeteeth/School-Security-System-Using-Facial-Recognition/assets/91562191/1a4e4ed0-a57a-401c-bbf5-7e14c9a4c7df)

This plot shows that class 'Hritesh' returns the highest AUC of 0.97, hence indicating excellent classification performance for this class, while classes like 'Karim' and 'Krishna' returned a pretty poor AUC value of 0.61, hence their poor classification performance. The ROC curve helps to draw competition between TPR and FPR for each single class. The top-left corner has good classification performance since this point maximizes the rate of true positives with a minimum false positive rate. 


Our project demonstrates variable performance across different classes, with precision ranging from 0.50 to 1.00, recall from 0.33 to 1.00, and F1 scores from 0.33 to 0.94, while achieving an overall accuracy of 0.75, indicating robust performance in certain scenarios but room for improvement in others.


