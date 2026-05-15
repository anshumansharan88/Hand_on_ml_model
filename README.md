# Hand_on_ml_model

California House Pricing Prediction 🏡
Overview
This project is an end-to-end machine learning model designed to predict median house values in Californian districts based on various local features. It is deeply inspired by the workflow presented in Aurélien Géron's highly acclaimed book, Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow. The project demonstrates core data science methodologies, ranging from data acquisition and exploratory data analysis (EDA) to data preprocessing, pipeline creation, and model evaluation.

Dataset
The dataset used in this project is the California Housing Dataset, which contains housing data drawn from the 1990 U.S. Census.

Target Variable: median_house_value - The median property value for a specific district.

Features: Includes metrics such as population, median income, housing median age, total rooms, total bedrooms, latitude, longitude, and ocean proximity.

Project Workflow
Data Fetching & Loading: Automated retrieval of the compressed dataset from the source repository and extracting it into a structured Pandas DataFrame.

Exploratory Data Analysis (EDA): Analyzing feature distributions, visualizing geographical mapping, identifying missing values (e.g., in the total_bedrooms column), and checking correlations between features and the target variable.

Data Preprocessing & Feature Engineering:

Imputing missing numerical values using SimpleImputer (median strategy).

Encoding categorical variables (handling the ocean_proximity text attribute).

Feature scaling to ensure all numerical inputs have a consistent scale for optimal model performance.

Model Selection & Training: Training regression models (such as Linear Regression, Decision Trees, and Random Forests) to accurately predict continuous housing prices.

Model Evaluation: Validating the accuracy of the predictions using standard regression metrics like Root Mean Squared Error (RMSE).

Technologies & Libraries Used
Python: Core programming language.

Pandas & NumPy: For robust data manipulation and numerical computations.

Scikit-Learn: For machine learning algorithms, data imputation, and evaluation metrics.

Matplotlib & Seaborn: For generating intuitive data visualizations and plots.

Jupyter Notebook: As the primary interactive development environment.

How to Run
Clone this repository to your local machine.

Ensure you have a Python environment set up (version 3.5+ recommended).

Install the required dependencies:

Bash
pip install pandas numpy scikit-learn matplotlib seaborn
Open the Jupyter Notebook predict_house_priceing.ipynb and run it cell by cell to observe the data pipeline and model results.

Author
Anshuman Sharan A third-year BTech student at Rungta College of Engineering and Technology, Bhilai, originally from Araria, Bihar. As an aspiring Data Scientist, I am passionate about extracting actionable insights from data and building predictive models. I specialize in Python and its data libraries, alongside strong foundational skills in SQL and Power BI visualization.
