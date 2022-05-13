# Spam-email-Detection
Implementation of a machine learning model to predict whether a message is spam or not. Furthermore, you will create a system that upon receipt of an email message will automatically flag it as spam or not, based on the prediction obtained from the machine learning model

# AWS Services Used
  1. **Sagemaker** to build and train and spam filter ML model
  2. **AWS s3 bucket** to store emails which can be further analysed for spam detection
  3. **SES** to set up an email address that upon receipt of an email will save it in s3
  4. **CloudFormation** for representing the infrastructure resources and permissions

# Architecture Diagram
  

 
 <img width="671" alt="Screen Shot 2022-05-05 at 11 01 01 PM" src="https://user-images.githubusercontent.com/17768756/167059816-a1aa0df5-4f6f-47c2-82b0-2ccc1f7070ff.png">

# Output
<img width="1137" alt="Screen Shot 2022-05-05 at 11 50 57 PM" src="https://user-images.githubusercontent.com/17768756/167064005-05858933-9a14-48da-87a3-0146cffdafd5.png">
