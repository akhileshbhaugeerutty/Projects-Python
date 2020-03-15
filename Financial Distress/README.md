# Financial Distress

Classification & Regression to understand Financial Distress on various companies. 

### Getting Started

The folder contains the Jupyter Notebook, coded in Python (ipnyb) and the PowerPoint presentation. For ease of use and access, the latter has been converted to a .pdf.

### Pre-Requisites

- Python packages: pandas, numpy, seaborn, sklearn.
- Download the DataFrame from [Kaggle](https://www.kaggle.com/shebrahimi/financial-distress), and modify the first instruction of the Notebook. 

### DataFrame

- 3672 observations of 84 variables. The target variable is 'Financial Distress', a continuous variable where > -0.5 indicates a healthy company. 
- Hold-Out Set made with 30% of all observations, and stratified sampling to conserve all proportions.
- Scaling of Data for faster calculations

### Algorithms & Methods

- The Cross Validations used to fine the best tuning parameters take quite some time. The best parameters found on my computer have been saved below the instructions. 
- Problem seen as both Classification & Regression, and the methods are commonly known as having both types of algorithms. <br>
Algorithms used (6 in total): 
  1. Random Forests
  2. Gradient Boosting
  3. Support Vector Machines
  
### Scoring

*Skewed* Data: much more healthy companies than in financial distress. --> biased Accuracy, so **F-Score** is used. <br>
A classification according to a certain threshold is made after the Regression in order to use the same scoring indicators, and compare Regression & Classification.

## Author

* **Akhilesh Bhaugeerutty** - Université Paris-Dauphine (PSL)
