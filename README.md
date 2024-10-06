
# Heart Disease Prediction

This project focuses on predicting the likelihood of heart disease in patients using a machine learning model. The dataset used includes medical information such as age, cholesterol levels, blood pressure, and other health indicators. The goal is to classify patients as either having a high risk of heart disease or not.

## Project Structure

- **Heart_Disease_Prediction.ipynb**: The main Jupyter Notebook where data preprocessing, exploratory data analysis, and model building are performed.

## Requirements

To run this notebook, you'll need to install the following Python packages:

- `pandas`: For data manipulation and analysis
- `numpy`: For numerical computations
- `matplotlib` and `seaborn`: For data visualization
- `scikit-learn`: For building and evaluating the machine learning model

You can install these packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run

1. Clone this repository to your local machine:

```bash
git clone <repository-url>
```

2. Install the required packages (as mentioned in the **Requirements** section).

3. Open the `Heart_Disease_Prediction.ipynb` file in Jupyter Notebook or JupyterLab:

```bash
jupyter notebook Heart_Disease_Prediction.ipynb
```

4. Run all the cells to see the exploratory data analysis and the machine learning model training process.

## Dataset

The dataset contains several features related to patients' health conditions, such as:

- Age
- Gender
- Cholesterol levels
- Blood pressure
- Chest pain type
- Resting heart rate
- Maximum heart rate achieved
- Presence of angina during exercise

The target variable indicates whether the patient is at high risk of heart disease.

## Machine Learning Model

The machine learning model used in this project is a classification model that predicts the likelihood of heart disease based on the patient's medical data. Various algorithms like Logistic Regression, Decision Trees, and Random Forests may be explored in the notebook.

## Results

After building and training the model, performance is evaluated using metrics like accuracy, precision, recall, and F1-score. Visualizations are provided to understand the feature importance and model behavior.

## Contributions

Feel free to contribute to the project by opening a pull request or submitting issues.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
