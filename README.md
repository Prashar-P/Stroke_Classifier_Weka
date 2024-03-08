<h3 align="center">Weka based Classifier for Stroke Analysis</h3>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#built-with">Datasets</a></li>
        <li><a href="#built-with">Classifiers</a></li>
      </ul>
      <a href="#contact">Contact</a>
    </li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

Analysis on dataset obtained from Kaggle to classify patients who have had/have not had a stroke. Project aims to to apply various techniques to dataset in order to balance,identify and classify data.

Hypothesis:
•	A high blood pressure can increase the likelihood of a stroke - As a higher blood pressure can weaken vessels causing them to burst.
•	Additional health conditions can be an increase the risk of stroke - Poor health can lead to weakened blood vessels and higher chances of blood clots. e.g obesity, smoking, alcohol.

NOTE: FULL WRITTEN REPORT HAS BEEN TEMPORARILY OMITTED.

### Built With

* [Weka-Installation]

### Datasets

Dataset used for analysis: [Stroke-Dataset]

The dataset contains 12 attributes as listed below:
•	Unique ID: Unique ID Number for each patient.
•	Gender: Patients gender (Male,Female,Other).
•	Age: Patients Age (Numeric Value from 0-82). • Hypertension: If Patient has a high blood pressure. (Binary Value: 0 - No Hypertension ; 1 - Hypertension).
•	Heart Disease: If Patient has a Heart Disease. (Binary Value: 0 - No Heart Disease ; 1 - Heart Disease). • Ever Married: Patients Marital Status (Binary Values Yes/No).
•	Work Type: Patients Occupation Type (Nominal Values: Children ; Govt Job ; Never Worked ; Private ; Self Employed). • Residence Type: Patients Home Area (Binary Value: Rural or Urban)
•	Average Glucose Level (Numeric Value from 50-300).
•	BMI: Body Mass Index (Numeric Value from 10-100) - Note: If values are: Below 18.5 = Underweight, 18.5-24.9 = healthy weight, 25-29.9 = Overweight, 30+ = Obese.
•	Smoking Status: Patients smoking status (Nominal Values: Formerly Smoked, Never Smoked, Smokes, Unknown) Note: Unknown Values correspond to missing values, we will be dealing with these in our data preprocessing.

When preprocessing the following techniques have been applied:
* Feature Selection
* Standardisation
* Replacing Missing/Null Values
* Removal of outliers
* SMOTE

### Classifiers

![image](https://github.com/Prashar-P/Stroke_Classifier_Weka/assets/140114811/8c8defb8-82ae-4405-81b1-2895430c3f82)

![image](https://github.com/Prashar-P/Stroke_Classifier_Weka/assets/140114811/d944a66f-d1de-4961-bdba-adf11799c596)

### Comparison to other work

Effects of smoking on stroke (Biqi Pan, Xiao Jin, Liu Jun, Shaohong Qiu, Qiuping Zheng, Mingwo Pan, 2019. The relationship between smoking and stroke. Medicine (Baltimore)):

![image](https://github.com/Prashar-P/Stroke_Classifier_Weka/assets/140114811/23f9f297-74bf-40a1-874e-9cf23a647f4a)

Classifiers using same dataset (Elias Dritsas and Maria Trigka, 2022. Stroke Risk Prediction with Machine Learning Techniques. Sensors (Basel)):

![image](https://github.com/Prashar-P/Stroke_Classifier_Weka/assets/140114811/471c11e4-884c-4bf7-bf63-85356795624d)

<!-- CONTACT -->

## Contact

[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn - Priya Prashar](https://www.linkedin.com/in/priya-prashar-4801/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-url]: https://www.linkedin.com/in/priya-prashar-4801/
[stroke-dataset]: https://sourceforge.net/projects/weka
[Weka-Installation]: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset/data


