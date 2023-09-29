# Heart disease Project
This is a project with the goal of developing a machine learning model that is capable of predicting if a patient has heart disease or not depending on the patient's medical files/record. 

# Project overview

## Project Description
Welcome to the "Predicting Heart Disease with Machine Learning" project repository. This project leverages data science and machine learning techniques to develop a robust predictive model for assessing the presence of heart disease in individuals based on their medical data. This project will analyze a variety of individual attributes, such as age, gender, cholesterol levels, blood pressure, and more. Its primary objective is to provide healthcare professionals with an efficient tool for promptly assessing the potential risk of heart-related issues in patients, enabling them to offer more effective care and treatment.

## About the Data
The original data is found from the Cleavland data from the UCI Machine Learning Repository. [Project data](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
There is also a version of it available on Kaggle. [Kaggle version of data](https://www.kaggle.com/datasets/ketangangal/heart-disease-dataset-uci)

## Table of Contents
- [Setup](#setup)
- [Usage](#usage)
- [Data and Datasets](#data-and-datasets)
- [Contributing](#contributing)
- [License](#license)
- [Authors and Acknowledgments](#authors-and-acknowledgments)
- [Project Status](#project-status)
- [Contact](#contact)

## Setup
To run this project, ensure you have Python 3.7 or later installed. You can set up the required Python environment and install the necessary packages using the .yml file included in the repository files.

To use this repository,
- clone it to your local machine using the code below;
  ```git clone https://github.com/Dee-ui/heart_disease_project.git```
- Navigate to project directory;
    ```cd heart_disease_project```
- Run the Jupyter Notebook to explore the project and execute the machine learning model;
    ```jupyter notebook end-end-heart-disease-classification.ipynb```

## Data and Datasets
The project's data and datasets can be found in the data directory. The features of the dataset where different information about each of the features in the data can be gotten by doing personal research(such as looking at the links above) or by talking to a subject matter expert (someone who knows more about the dataset). The data dictionary is shown below;
**Data dictionary**

1. age - age in years
2. sex - (1 = male; 0 = female)
3. cp - chest pain type
    * 0: Typical angina: chest pain related decrease blood supply to the heart
    * 1: Atypical angina: chest pain not related to heart
    * 2: Non-anginal pain: typically esophageal spasms (non heart related)
    * 3: Asymptomatic: chest pain not showing signs of disease
4. trestbps - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern
5. chol - serum cholestoral in mg/dl
    * serum = LDL + HDL + .2 * triglycerides
    * above 200 is cause for concern
6. fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
    * '>126' mg/dL signals diabetes
7. restecg - resting electrocardiographic results
    * 0: Nothing to note
    * 1: ST-T Wave abnormality
        * can range from mild symptoms to severe problems
        * signals non-normal heart beat
    * 2: Possible or definite left ventricular hypertrophy
        * Enlarged heart's main pumping chamber
8. thalach - maximum heart rate achieved
9. exang - exercise induced angina (1 = yes; 0 = no)
10. oldpeak - ST depression induced by exercise relative to rest looks at stress of heart during excercise unhealthy heart will stress more
11. slope - the slope of the peak exercise ST segment
    * 0: Upsloping: better heart rate with excercise (uncommon)
    * 1: Flatsloping: minimal change (typical healthy heart)
    * 2: Downslopins: signs of unhealthy heart
12. ca - number of major vessels (0-3) colored by flourosopy
    * colored vessel means the doctor can see the blood passing through
    * the more blood movement the better (no clots)
13. thal - thalium stress result
    * 1,3: normal
    * 6: fixed defect: used to be defect but ok now
    * 7: reversable defect: no proper blood movement when excercising
14. target - have disease or not (1=yes, 0=no) (= the predicted attribute)
For a more detailed description of the dataset, refer to the kaggle link;
[Kaggle version of data](https://www.kaggle.com/datasets/ketangangal/heart-disease-dataset-uci)

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please review our contribution guidelines before getting started.

## License
This project is licensed under the MIT License.

## Authors and Acknowledgments
Agbonoga Dauda: Project Lead.
ztm academy.
Special thanks to the Kaggle community and the Kaggle "Heart disease Prediction" competition organizers for providing the dataset and inspiration for this project.

## Contact
For questions, feedback, or collaboration inquiries, please contact Agbonoga Dauda at;
```daudaagbonoga@gmail.com```
