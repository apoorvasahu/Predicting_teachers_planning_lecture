# Description: 
Predicting whether the teacher will plan the lecture or not. Teachers add classwork content(stories, videos, pdf, ppt, doc, etc.) for the live lectures for better engagement.  

DataFrame -Teacher_ID, Gender, Total_Lectures_Conducted_until_now , Library_content_per_day, Education/Qualification, Assignments_Daily, Weekly_Tests, School_Groups, Avg_duration_lec_min and Classwork_Added. 

# DataSet: 
https://drive.google.com/file/d/1HwwvQr7nfAD8YkRF-ivduTkTVN9avm6K/view?usp=sharing

# Python Libraries Used: 
numpy,

pandas,

matplotlib,

seaborn,

warnings,

from sklearn.preprocessing import LabelEncoder  [Converting category labels into numerical using LabelEncoder]

from sklearn.preprocessing import StandardScaler [To bring all the features to the same scale]

from sklearn.model_selection import train_test_split 

from sklearn.model_selection import GridSearchCV

from sklearn.linear_model import DecisionTreeClassifier

from sklearn.ensemble import RandomForestClassifier

from sklearn.neighbors import KNeighborsClassifier


# Set up 
$ pip install numpy

$ pip install pandas

$ pip install matplotlib

$ pip install seaborn

$ pip install -U scikit-learn

# Conclusion:

Accuracy is highest in Random Forest Classifier, 70%. 

No noticable effect of campaign on classwork. So Teachers pre-planning lectures and not preplanning are 50-50 distributed. 

Teachers adding library content on the OS Platform is the most important feature related to teachers pre-planning lecture.

