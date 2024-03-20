# Project_4_Team5
Repository for Project #4 (Final Project)

**Overview**
This project focuses on the analysis of a dataset comprising 1904 patient IDs of individuals who have suffered from breast cancer. The dataset contains a wide range of information, including basic demographics such as age at diagnosis and type of cancer, as well as more complex data such as tumor characteristics, overall survival rate, menopausal stage, months of survival, and detailed genetic information. The primary goal of this analysis is to evaluate various factors that may impact treatment outcomes and survival rates in patients with breast cancer.

**Dataset Description The dataset includes the following key variables:**
Patient ID: Unique identifier for each patient in the dataset. Age at Diagnosis: Age of the patient at the time of breast cancer diagnosis. Type of Cancer: Specific subtype or type of breast cancer diagnosed. Tumor Characteristics: Detailed information about the tumor, including size, stage, and grade. Overall Survival Rate: Survival status of patients and their survival time in months. Menopausal Stage: Menopausal status of the patients. Genetic Information: Additional detailed genetic data related to breast cancer.

**Analysis Methods The analysis workflow includes the following steps:**
Descriptive Statistics: Exploratory data analysis to understand the distribution and characteristics of the dataset. Dynamic Visualizations: Utilizing Tableau for interactive and customized visualizations, including calculated fields and metrics. Data Cleaning and Formatting: Removing irrelevant columns and standardizing value formats for consistency. Machine Learning Model: Implementing a machine learning algorithm to predict survival rates with a 90% accuracy rate. User-Friendly Tool: Creating a simple form based on the machine learning model to calculate survival rates based on user inputs. Website Integration: Incorporating both the descriptive analysis and predictive model into a website using HTML code for user interaction.

Contributions and Feedback Contributions to this project are welcome through pull requests. If you have any feedback, suggestions, or questions, please open an issue in the repository.

One of the major limitations of this analysis is the lack of medical knowledge from the analysts and the limited details in the original dataset. The dataset was rich in genetic information, which presented challenges in defining its repercussions and understanding its full impact on treatment outcomes and survival rates.

**Predict breast cancer survival using machine learning models**
The most important part of a process of clinical decision-making in patients with cancers, in general, is the accurate estimation of prognosis and survival duration. Breast cancer patients with the same stage of the disease and the same clinical characteristics can have different treatment responses and overall survival.

**Deep learning model predictions**

Data Source:
www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric​

Model: ​
-Neural Networks.​

Variable aimed to predict: ​
-Overall survival.​

Features of the model: ​
-Age at Diagnosis. ​

Type of Cancer.​
-Tumor Detailed information about the tumor, including size, stage, and grade. ​

Treatment procedure. ​
-Overall Survival rate.​
-Genetics attributes.

**Read and clean the data**
![NN_model_1](https://github.com/rodrigonmo3020/Project-4/assets/144175033/a0710dcd-bf14-4db2-ba48-81afdc96c36a)

**Creating a neural network model by assigning the number of input features and nodes for each layer using Tensorflow and Keras**
![NN_model_2](https://github.com/rodrigonmo3020/Project-4/assets/144175033/e12a077e-001e-4251-b83d-9ca36d8cae5b)

**Evaluate the model’s performance by generating an accuracy score.**
![Accuracy](https://github.com/rodrigonmo3020/Project-4/assets/144175033/bd2e5630-de09-4819-95fb-998fb42a52f3)

**Gene clustering**
![elbow_courve](https://github.com/rodrigonmo3020/Project-4/assets/144175033/f59f3a61-404c-4328-8e85-208b22356cbd)

![scatter_1](https://github.com/rodrigonmo3020/Project-4/assets/144175033/fcde8345-fc2f-4a05-92cf-e25f39d31214)

![scatter_2](https://github.com/rodrigonmo3020/Project-4/assets/144175033/3afe2e5c-ba3f-4285-b841-0a4522cbe799)

**Flask application**
To create a user-model interaction, we implemented an html python connection using flask, first following the ETL process, We extract the data from the CSV and proceed to clean and transform it.
![Flask_1](https://github.com/rodrigonmo3020/Project-4/assets/144175033/7648674a-263f-4945-b5ac-10dd4451d771)

Then we proceed to the model training using a logistic regression, also printing in the console the model score
![Flask_2](https://github.com/rodrigonmo3020/Project-4/assets/144175033/a9abffef-eaf9-4596-9d82-244ac69c1023)

Once model trained, we proceed collecting data from user, we achive so by implementing a form and requesting with flask those results.
![Flask_3](https://github.com/rodrigonmo3020/Project-4/assets/144175033/c8e09485-99d9-42fa-b270-3624eeddd807)

Finally we transform the data provided by the user to feed the model and make a prediction
![Flask_4](https://github.com/rodrigonmo3020/Project-4/assets/144175033/a48b3cd5-441b-4198-9088-b86207756c02)


**CONCLUSION**
​Cancers are associated with genetic abnormalities. Gene expression measures the level of gene activity in a tissue and gives information about its complex activities. Using machine learning techniques on genetic data has the potentials of giving the correct estimation of survival time and can prevent unnecessary surgical and treatment procedures.


