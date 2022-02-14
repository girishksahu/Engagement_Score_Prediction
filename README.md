# Engagement_Score_Prediction
Part of JOB-A-THON Challenge by Analytics Vidhya

- ABC is an online content sharing platform that enables users to create, upload and share the content in the form of videos. It includes videos from different genres like entertainment, education, sports, technology and so on. The maximum duration of video is 10 minutes.

- Users can like, comment and share the videos on the platform. 

- Based on the user’s interaction with the videos, engagement score is assigned to the video with respect to each user. Engagement score defines how engaging the content of the video is.

- Understanding the engagement score of the video improves the user’s interaction with the platform. It defines the type of content that is appealing to the user and engages the larger audience.

### **Objective**

- The main objective of the problem is to develop the machine learning approach to predict the engagement score of the video on the user level.

### **Submission**
- Deliverable: **Engagement Score Prediction**

- Machine Learning Task: **Regression**

- Target Variable: **engagement_score**

### **Evaluation Metric**

- The model evaluation will be based on the R2 score.

### **Data Description**
- The **dataset** consists of all the necessary information related to Engagement Score.


| Records | Features | Dataset Size |
| :-- | :-- | :-- |
| 89197 | 10 | 6.8+ MB | 

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **row_id**   | Unique identifier of the row |
|02| **user_id**      | Unique identifier of the user|
|03| **category_id**        | Category of the video|
|04| **video_id**          | Unique identifier of the video|
|05| **age**      | Age of the user |
|06| **gender**           | Gender of the user (Male and Female)|
|07| **profession**     | Profession of the user (Student, Working Professional, Other)|
|08| **followers**        | No. of users following a particular category |
|09| **views**          | Total views of the videos present in the particular category    |
|10| **engagement_score**         |Engagement score of the video for a user  |
