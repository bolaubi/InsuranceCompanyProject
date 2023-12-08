# Insurance Company Project

![InsuranceCompany-Illustration](pic/mediensturmer.jpg)

Photo by [Medienstürmer](https://unsplash.com/@medienstuermer) on [Unsplash](https://unsplash.com/photos/two-people-sitting-during-day-aWf7mjwwJJo)

## 01: Project File Descriptions

**Note: Please check the files that are in bold*

1. ***DS-Insurance-BenedictLaiman-Slides.pptx --> presentation in pptx format***
2. DS-Insurance-BenedictLaiman-Slides.pdf --> presentation in pdf format
3. data-ds.csv --> raw data
4. data-cleaned.csv --> data that have been preprocessed
5. ***01-BenedictLaiman-DS-PP.ipynb --> Preprocessing + EDA Notebook***
6. ***03-BenedictLaiman-DS-model-BC.ipynb --> Binary Classification Project***
7. ***04-BenedictLaiman-DS-model-RS.ipynb --> Recommender System Project***
8. ***05-BenedictLaiman-DS-model-CS.ipynb --> Customer Segmentation Project***
9. pic --> Folder containing exported images for presentation & selected slides for readme markdown
10. condaEnv_oldBase.yaml --> The Conda environment to run these files



## 02: Project Table of Content

- ***01: Introduction** | **[File: 01-BenedictLaiman-DS-PP.ipynb]***
- **02:** Exploratory Data Analysis
  - 02.01: Importing Libraries
  - 02.02: Importing Data
  - 02.03: Data Understanding
  - 02.04: Preprocessing + Feature Engineering Part 1
- **02.05:** Checking the Descriptive Statistics
  - 02.05a: Checking the Descriptive Statistics - Numerical Features
  - 02.05b: Checking the Descriptive Statistics - Categorical Features
  - 02.05c: Categorical Features - further preprocessing
  - 02.05d: Exporting Data Frame to CSV

- ***03.01: Introduction | [File: 03-BenedictLaiman-DS-model-BC.ipynb]***
- **03.02:** Preprocessing
- **03.03:** Creating benchmark classifier models
- **03.04:** Fine-tuning the benchmark classifier models
  - 03.04A: Tuning Logistic Regression Model
  - 03.04B: Tuning KNeighbors Model
  - 03.04C: Tuning Random Forest Classifier Model
  - 03.04D: Tuning Gradient Boosting Classifier Model
- **03.05:** Creating Final classifier model
- **03.06:** Monetary Value Performance of the Final Classifier Model
- ***04.01: Introduction | [File: 04-BenedictLaiman-DS-model-RS.ipynb]***
- **04.02:** Preprocessing
- **04.03:** User-based Collaborative Filtering | KNN-based Model
  - 04.03A: Preprocessing for KNN-based Model
  - 04.03B: Creating KNN-based Model
  - 04.03C: Testing the KNN-based Model
- **04.04:** User-based Collaborative Filtering | Pearson Correlation-based Model
  - 04.04A: Preprocessing for Pearson Correlation-based Model
  - 04.04B: Creating Pearson Correlation-based Model
  - 04.04C: Testing the Pearson Correlation-based Model
- ***05.01: Introduction | [File: 05-BenedictLaiman-DS-model-CS.ipynb]***
- **05.02:** Preprocessing
- **05.03:** Customer Segmentation Without Relying on Plan Code (CS General)
- **05.04:** Customer Segmentation Based on Plan Code (Plan Code-based CS)
- **05.05:** Customer Segmentation Based on 'Premium Amount' that Has Been Quantile-binned (Premium Amount-based CS)
- **05.06:** Overall Trend Findings - Customer Segmentation
- **06:** Further Insights

## 03: Introduction

***The primary goals of the project are as follows:***

1. Create a machine learning model to assist in **selecting potential customers**.

2. Develop a **recommendation engine** for new customers who share similar characteristics.

3. **Segment customers** based on their existing policies.

4. Extract **insights** from a given dataset.

   

***Dataset Description:***

1. ID = Row Reference
2. Customer ID = Customer unique ID
3. City Code = The code of the City
4. Region Code = The code of a region
5. Accomodation Ownership = Accomodation ownership type
6. Insurance Type = Type of insurance
7. Age = Customers' age
8. Married = Customers' Marital Status
9. Plan Code = Unique product code per insurance product
10. Policy Duration = Duration of active policy
11. Policy Type = Type of insurance policy (e.g there could be someone who buys an insurance policy only or an insurance policy plus a health rider)
12. Policy Category = Grouping category for the policy type (e.g. polis category A adalah polis tipe Health and Jiwa).
13. Premium Amount = The total amount of premiums we receive from insurance customers.
14. Response = Labels, 1 for customers that want to buy insurance/ good response from the customer, 0 for customers that do not want to buy insurance/ bad response from the customer.



## 04: Some Results

These are some of the results from the project. Please check the presentation as well as the notebook files for in-depth explanations.

![InsuranceCompanyProject_Page_01](pic\InsuranceCompanyProject_Page_01.jpg)

<hr>

![InsuranceCompanyProject_Page_02](pic\InsuranceCompanyProject_Page_02.jpg)

<hr>

![InsuranceCompanyProject_Page_05](pic\InsuranceCompanyProject_Page_05.jpg)

<hr>

![InsuranceCompanyProject_Page_07](pic\InsuranceCompanyProject_Page_07.jpg)

<hr>

![InsuranceCompanyProject_Page_08](pic\InsuranceCompanyProject_Page_08.jpg)

<hr>

![InsuranceCompanyProject_Page_09](pic\InsuranceCompanyProject_Page_09.jpg)

<hr>

![InsuranceCompanyProject_Page_11](pic\InsuranceCompanyProject_Page_11.jpg)

<hr>

![InsuranceCompanyProject_Page_16](pic\InsuranceCompanyProject_Page_16.jpg)

<hr>

## 05: Profile

© Benedict Laiman 2023

Get in touch with me through:

- [Linkedin](https://www.linkedin.com/in/benedictlaiman)
- [Discord](https://discordapp.com/users/525654231940857867/)



