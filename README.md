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
   * We used a very small training set, becasue the pandemic had only been going on for few months. We were inspired by several papers and models, such as the [COVID-Net](https://www.technologyreview.es/s/12049/una-nueva-ia-podriadetectar-el-covid-19-en-una-radiografia-de-torax)
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
