# WebCiter
Cyber criminals conduct phishing attacks using well-crafted URLs. They trick the user by having them click on a fake URL and getting them redirected to phishing websites to steal their information. To help businesses and people not to fall into the URL phishing trap, we adapted URL-based features in our Machine Learning algorithms (ML) to capture these phishing tricks and report them to the proper personnel. The goal of this project is to train machine learning models (ML), using 30 different features to predict whether a site is legitimate or phishing.

# What's included?
Dataset Link: https://www.kaggle.com/akashkr/phishing-url-eda-and-modelling/data

The dataset contain four primary features that comprise the system and each one of these features is divided into sub-features.

The four primary features are:
-	Abnormal Based
-	Address Bar Based
-	Domain Based
-	HTML and JavaScript Based

# Models & Training:
<<<<<<< HEAD
We will be using Akash Kumar’s dataset and features that he developed in his previous research, see link above. Kumar used “a simple tree-based classifier and no hyper-parameter tuning to model and test the dataset.” See details in this link: https://www.kaggle.com/akashkr/phishing-url-eda-and-modelling. On the other hand, our ML system will use different ML to see if these models will behave differently and render the desired results. Below are the models that we will be using:
=======
We will be using Akash Kumar’s dataset and features that he developed in his previous research. Kumar used “a simple tree-based classifier and no hyper-parameter tuning to model and test the dataset.” See details in this link: https://www.kaggle.com/akashkr/phishing-url-eda-and-modelling. On the other hand, our ML system will use different ML to see if these models will behave differently and render the desired results. Below are the models that we will be using:
>>>>>>> 23f9aef (updated dashboard)
- Logistic Regression
- K-Nearest Neighbor (KNN)
- Support Vector Machine (SVM)
- Random Forest

Since we are using binary classifiers, the Data values are converted to the following:
- Legitimate Site = 1
- Phishing Site = 0

# ML Models Results:
After training and testing the data using the four models above, we concluded that Random Forest is the winner among the four models, achieving an accuracy rate of 97%.

# Future Considerations:
For future work, we would like to build a fully interactive dashboard for the phishing detection system that will allow people to search and track URLs themselves. Also, we would like to include live learning so that new phishing attack patterns can constantly be learned and enhanced.

