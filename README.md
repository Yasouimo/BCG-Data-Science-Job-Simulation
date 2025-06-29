# BCG Data Science Job Simulation (Forage)  
**Feb 2025 - Mar 2025**

## Overview    
This repository contains the work completed during the BCG Data Science Job Simulation program. The project focused on analyzing customer churn, building predictive models, and delivering actionable insights to drive business decisions.

---

## Project Structure  

### **Task 1: Business Understanding & Hypothesis Framing**  
- Defined the business problem: Understanding customer churn and identifying key drivers.  
- Framed hypotheses to explore potential factors influencing churn, such as price sensitivity, tenure, and consumption patterns.  

### **Task 2: Exploratory Data Analysis (EDA)**  
- Conducted data cleaning and preprocessing using Python libraries like Pandas and NumPy.  
- Visualized data distributions and relationships using Matplotlib and Seaborn.  
- Key insights:  
  - Customers with shorter tenure are more likely to churn.  
  - Price sensitivity and sales channels showed varying churn rates.  

### **Task 3: Feature Engineering & Modelling**  
- Engineered features such as:  
  - Differences in off-peak prices between December and January.  
  - Average price changes across different periods.  
  - Customer tenure and months since contract updates.  
- Transformed categorical variables into numerical representations using Label Encoding.  
- Built and optimized a Random Forest model:  
  - Achieved **85% prediction accuracy**.  
  - Tuned hyperparameters using GridSearchCV to identify the best model configuration.  
- Evaluated model performance using metrics like accuracy, precision, and recall.  

### **Task 4: Findings & Recommendations**  
- Delivered an executive summary highlighting key drivers of churn:  
  - Net margin, forecast meter rent, and consumption over 12 months were top predictors.  
  - Price sensitivity was a weak contributor but required further experimentation.  
- Provided actionable recommendations to reduce churn and improve customer retention.  

---

## Tools & Technologies  
- **Programming Languages**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Techniques**: Exploratory Data Analysis, Feature Engineering, Random Forest Modelling, Hyperparameter Tuning  

---

## Key Achievements  
- **Analyzed customer churn** using Python for data processing and visualization.  
- **Developed an optimized Random Forest model** achieving 85% prediction accuracy.  
- **Delivered actionable insights** through an executive summary to drive business decisions at XYZ Analytics.  

---

## How to Use  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo/bcg-data-science-simulation.git
   cd bcg-data-science-simulation
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

3. Explore the Jupyter Notebooks for each task:  
   - **Task 2**: `Exploratory_Data_Analysis.ipynb`  
   - **Task 3**: `Task_3_feature_engineering.ipynb`  
   - **Task 4**: `Task_4_modeling_starter.ipynb`  

---

## Contact  
For any questions or feedback, please reach out to [yahyabellmir@gmail.com](mailto:yahyabellmir@mail.com)
