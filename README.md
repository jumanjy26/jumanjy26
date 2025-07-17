# Patient No-Show Prediction

This project was completed as part of the **Data Mining** and **Foundations of AI** modules at the University of Derby. The objective was to predict whether a patient will attend or miss their scheduled medical appointment based on various features such as patient age, appointment time, and previous no-show status.

The project was implemented using **Google Colab** for ease of collaboration and access to resources.

## Datasets

This project uses the following datasets:
1. **Appointments Dataset**: Contains information about appointment schedules, patient IDs, status, and timing.
2. **Patients Dataset**: Contains demographic details such as age, sex, and insurance.
3. **Slots Dataset**: Contains available time slots for appointments.

## Steps Involved

1. **Exploratory Data Analysis (EDA)**:
   - Analysed the distribution of key features like patient age, appointment time slots, and no-show status.
   - Visualised the key data patterns using plots such as histograms, box plots, and correlation heatmaps.

2. **Data Preprocessing**:
   - Handled missing values.
   - Applied One-Hot Encoding for categorical variables (e.g., sex, appointment status).
   - Engineered additional features such as `days_until_appointment`.

3. **Modeling**:
   - Implemented machine learning models: Decision Tree, Logistic Regression, and Random Forest.
   - Evaluated models using accuracy, precision, recall, F1-score, and confusion matrices.

4. **Model Optimization**:
   - Performed hyperparameter tuning using `RandomizedSearchCV` for Random Forest and Decision Tree models.
   - Validated model performance using 5-fold cross-validation.

5. **Results**:
   - Achieved strong model performance with high accuracy, precision, recall, and F1-scores.

## Getting Started

### Prerequisites

You can run this project directly in **Google Colab** without needing to install any packages locally. However, if you'd like to run the code locally, you'll need the following Python libraries:
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

### How to Run the Project in Google Colab

**Open the Project:**

Open the provided Google Colab link for the notebook.

**Run the Cells:**

You can execute the cells in the notebook in sequence to load the data, perform the analysis, and train the models.

**Results:**

Visualisations, model evaluation metrics, and optimisation results will be displayed directly in the Colab environment.
