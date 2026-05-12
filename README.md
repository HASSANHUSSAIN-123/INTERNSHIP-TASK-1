Hassan Hussain
DHC-9759
**Internship Task 1 — Exploratory Data Analysis (EDA) on Iris Dataset**

**Overview:**
This project performs Exploratory Data Analysis (EDA) on the Iris dataset to understand the relationships between flower species and their features such as sepal length, sepal width, petal length, and petal width.

**Dataset:**
Name: Iris Dataset  
Source: Loaded directly from the `seaborn` library (`sns.load_dataset('iris')`)  
Shape: 150 rows × 5 columns
**Column**                   **Description**
sepal_length 	      Length of the sepal (cm)
sepal_width	        Width of the sepal (cm)
petal_length	      Length of the petal (cm)
petal_width	        Width of the petal (cm)
species            	Flower species (setosa, versicolor, virginica)

**Technologies Used**
**Library**                 **Purpose**
pandas	            Data loading, manipulation, and statistical analysis
seaborn	            Dataset loading and scatter plot visualization
matplotlib        	Histograms and box plot visualizations

**Tasks Performed**

1. Data Loading
Loaded the Iris dataset from seaborn's built-in datasets
Converted it into a pandas DataFrame for analysis

3. Data Exploration
Checked the shape of the dataset (rows and columns)
Explored column names
Displayed the first 5 rows using .head()
Used .info() for data types and non-null counts
Used .describe() for descriptive statistics (mean, std, min, max)

5. Data Quality Check
Checked for missing values using .isnull().sum()
Result: No missing values found in the dataset

7. Visualizations
Scatter Plots
Sepal Length vs Sepal Width
Petal Length vs Petal Width
Used to show relationships and correlations between features
Histograms
Distribution plots for all 4 numerical features
Helps understand value spread and frequency
Box Plots
Individual box plots for all 4 features
Used to detect outliers and understand data spread (IQR)

**Install required libraries**
pip install pandas seaborn matplotlib

**Project Structure**

Internship_task_1/
│
├── Internship_task_1.ipynb   # Main notebook with all code and output
└── README.md                 # Project documentation (this file)

Key Findings
The dataset contains no missing values, making it clean and ready for analysis
Petal length and petal width show a strong positive correlation
Sepal width has a few visible outliers based on box plot analysis
Histograms reveal that petal measurements have a bimodal distribution, suggesting clear separation between species
