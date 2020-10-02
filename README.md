# Andres Michel  _   Data Science Portfolio
 
 Hi, this is a compilation of a few projects that I've worked on, mostly in the fields of Machine Learning, Deep Learning, computer vision, as well as data analysis. This series
 of projects were part of the MCC program I'm currently attending to, the IBM Data Science Professional Certification course or simple personal projects I've come up with 

 
# [1. Seattle Car Collision predictive Analysis - Predictive analysis of severe car crashes](https://github.com/andresmichel92/Coursera_Capstone)
Motor vehicle road accidents is a leading cause of death, and having enough data accounting for location, vehicle characteristics, road and weather conditions as well as the outcome (Severity of car crash) can be used to build a model that predicts the chances of a high severity car crash to occur under certain conditions.
  * I used the Seattle GIS collision data, provided by the city of Seattle. This includes all types of collisions from 2004 to present. 
  * The data consists of 37 attributes and 194,673 rows (or acidents) which after cleansing activities, was reduced to 182,660 rows.
  * This project was the Capstone Project for the IBM Data Science Professional Certification.
Below are some sample images of the EDA performed and the outcome of the analysis:
<div>
 <div>
<img src="https://raw.githubusercontent.com/andresmichel92/DS_Portfolio/main/images/Collisions_by_hour_day.PNG" width="70%">
 </div>
 <div>
<img src="https://raw.githubusercontent.com/andresmichel92/DS_Portfolio/main/images/Collisions_ROC.PNG" width="30%">
 </div>
</div>

# [2. COVID 19 classifciation of Chest X-rays  - Transfer Learning Computer Vision models](https://colab.research.google.com/drive/1c44W0fMiaeEkBQt8RXbMFAD5BDwTeQi4?usp=sharing)
   * This project was part of the Deep Learning Topics Course of the MCC Program.
   * As part of this project we had to come up with a useful model to identify COVID 19 patients based on Chest X-rays.
   * We used a very small training set, becasue the pandemic had only been going on for few months. We were inspired by several papers and models, such as the [COVID-Net](https://www.cdc.gov/coronavirus/2019-ncov/covid-data/covid-net/purpose-methods.html)
   * Due to GPU limitations, we opted not to use data augmentation techniques, and used transfer learning models instead, such as: VGG16, ResNet, MobileNet, GoogleLeNet, EfficientNet, amongh others, which are available in the Keras library.
   * For instance, the EfficientNet obtained an **accuracy of .92** 
<div>
 <div>
<img src="https://raw.githubusercontent.com/andresmichel92/DS_Portfolio/main/images/covid_test.PNG" width="20%">
 </div>
 <div>
<img src="https://raw.githubusercontent.com/andresmichel92/DS_Portfolio/main/images/model.PNG" width="50%">
 </div>
</div>

# [3. College Student Dropout unsupervised analysis and remediation measures evaluation](https://github.com/andresmichel92/College_Students_R)
This project consisted of an analysis of College Students dropouts from a sample of 1000 students.

The dataset consisted of several .csv sources, College Entry test results, Academic information for each Subject, Class, test and project throught the duration of the career, as well as prior academic background, financial information regarding socio-economics and tuition payment records.

1. Clean data, integrate data into a single dataframe (after performing some simple feature engineering to each source)
2. Upon the cleansing and integration of the data, I performed a cluster analysis, in order to identify groups of bad-performing students. Meaning, those that are more prone to drop-out. Then proceeded to label the students in said group.
3. Train a ML neural network to identify students falling into said "Dropout candidates" group
4. Develop an algorithm to propose remediation measures tailored to each student. This was a genetic algorithm that performed the analysis of each remediation measure, optimizing for efficiency in moving students away from the Dropout candidates group and maximizing the resources available (money).
<div>
 <div>
<img src="https://raw.githubusercontent.com/andresmichel92/DS_Portfolio/main/images/R_map.PNG" width="50%">
 </div>
 <div>
<img src="https://raw.githubusercontent.com/andresmichel92/DS_Portfolio/main/images/R_project_corrplot.PNG" width="50%">
 </div>
</div>

# [6. Skin Cancer identification - image metadata EDA](http://localhost:8888/notebooks/Desktop/ISIC-2019-EDA.ipynb)
This is my part of my thesis. My project consists on building a model that can predict the presence of Melanoma skin cancer on early stages. The system will also perform a feature extraction, in order to provide relevant information to the medical team in order to understand the outcome of the model.
<div>

<img src="https://raw.githubusercontent.com/andresmichel92/DS_Portfolio/main/images/Melanoma_age.PNG" width="45%">

<img src="https://raw.githubusercontent.com/andresmichel92/DS_Portfolio/main/images/Melanoma_location.PNG" width="45%">

</div>

# [5. Fuel consumption Regression Analysis](https://github.com/andresmichel92/MCC-python-DS/blob/master/Kaggle-CTR/Fuel%20Consumption%20-%20Regression.ipynb)
 This project was simply about finding the best possible regression method for the Fuel consumption vs CO2 emision relationship among cars based on number of cylinders and engine size.
<div>

<img src="https://raw.githubusercontent.com/andresmichel92/DS_Portfolio/main/images/Fuel_consumption_features.PNG" width="45%">

<img src="https://raw.githubusercontent.com/andresmichel92/DS_Portfolio/main/images/Fuel_consumption_Polynomial_regression.PNG" width="45%">

</div>
 
