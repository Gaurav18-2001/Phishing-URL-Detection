# Phishing-URL-Detection
Aim is to detect phishing URLs as well as narrow down to best machine learning algorithmby comparingaccuracy rate, false positive and false negative rate.

Phishing becomes a main area of concern for security researchers because it is not difficult
to create the fake website which looks so close to legitimate website. Main aimof theattacker is to steal banks account credentials. Phishing attacks are becoming successful because lack of user awareness. The general method to detect phishing websites by updating blacklisted URLs, Internet
Protocol (IP) to the antivirus database which is also known as “blacklist" method. To overcome the drawbacks of blacklist and heuristics-based method, many securityresearchers now focused on machine learning techniques. Using this technique, algorithm will analyze various blacklisted and legitimate URLs andtheir features to accurately detect the phishing websites including zero-hour phishing websites. 

For our study, a large number of phishing pages were necessary. We concatenated three databases from Kaggle and merged it into one. The information collected by this methodis freely available and the amount of reported phishing sites is very large.

Depending on the data type (qualitativeor quantitative)of the target variable (commonly referred to as the Y variable) we are  going to be building a classification model. We will be using logistic regression, MultinomialNB and Random Forest.


![image](https://user-images.githubusercontent.com/63391946/168397018-90190268-62e5-4e2e-8488-71626087db2c.png)


The output of front end is gonna look like this:
![image](https://user-images.githubusercontent.com/63391946/168423299-3f171e78-f595-43b8-8072-cf8013dfcfa1.png)

For a genuine site:


![image](https://user-images.githubusercontent.com/63391946/168423330-45812eb6-46e9-4027-a98e-8d6ab94adad0.png)

For a phishing site:


![image](https://user-images.githubusercontent.com/63391946/168423367-291e5cee-a685-4989-b730-87f9f504faa6.png)
