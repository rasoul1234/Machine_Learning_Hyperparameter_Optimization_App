


# Machine Learning Hyperparameter Optimization App (Regression Edition)
### Link: 🚀 Excited to Share My Latest Project: Machine Learning Hyperparameter Optimization App 🤖

I’m thrilled to announce the launch of my Machine Learning Hyperparameter Optimization App, designed to help data scientists and machine learning enthusiasts quickly fine-tune models and optimize hyperparameters for better performance.

Key Features: 🔍 Random Forest Regressor to predict continuous variables. ⚙️ Hyperparameter Tuning via GridSearchCV to improve model performance. 📊 Interactive Data Visualizations with Plotly to analyze model metrics. 📈 CSV File Upload and model building made easy. 💾 Downloadable Model Performance Results in CSV format.

Feel free to explore the app, test it out with your own datasets, and optimize machine learning models with ease. 🔧

Check it out here: https://machinelearninghyperparameteroptimizationapp-kzer9i7m9aopvizdp.streamlit.app/

#MachineLearning #DataScience #AI #ArtificialIntelligence #DataVisualization #Streamlit #Python #DataScienceProjects



This Streamlit application allows users to perform hyperparameter tuning for a regression model using the **Random Forest** algorithm. The app provides an interactive interface to upload datasets, set hyperparameters, and visualize the model's performance.

---

## Features

- Upload CSV datasets for analysis.
- Split data into training and testing sets.
- Use **Random Forest Regressor** to build a regression model.
- Perform **GridSearchCV** for hyperparameter tuning.
- Visualize the results of hyperparameter tuning in 3D using Plotly.
- Download performance metrics and grid search results as CSV files.

---

## How to Use

### 1. Installation
Clone this repository and install the required dependencies:
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt


### 2. Running the Application
Start the Streamlit app:
```bash
streamlit run app.py
```

### 3. App Interface
- **Upload Data**: Use the sidebar to upload your CSV file or load the example **Diabetes** dataset.
- **Set Parameters**: Adjust hyperparameters for Random Forest, such as:
  - Number of estimators (`n_estimators`)
  - Maximum features (`max_features`)
  - Minimum samples for splitting/leaves (`min_samples_split`, `min_samples_leaf`)
  - General options like random state, bootstrap, and performance metrics.
- **Model Building**: The app splits data, tunes hyperparameters using **GridSearchCV**, and evaluates the model.
- **Visualize Results**: View a 3D surface plot of hyperparameter tuning results.
- **Download Results**: Download the grid search results and model performance metrics.

---

## Dependencies

The app requires the following Python packages:
- `streamlit`
- `pandas`
- `numpy`
- `plotly`
- `scikit-learn`

Install them with:
```bash
pip install -r requirements.txt
```

---

## Example Dataset

An example dataset (Diabetes dataset) is included in the app for demonstration purposes. To use it:
1. Leave the file uploader empty.
2. Click the **Press to use Example Dataset** button.

---

## Project Structure

```plaintext
.
├── app.py                  # Main Streamlit app script
├── requirements.txt        # Required Python dependencies
└── README.md               # Project documentation
```

---

## Author

Developed by **Muhammad Rasoul Sahibzadah**. For more information, visit [AUAF](https://auaf.edu.af/).

---

## License

This project is licensed under the [MIT License](LICENSE).


### **Additional Notes**
- Update the placeholder `yourusername/your-repo-name` with the actual GitHub repository URL if hosting the project on GitHub.
- Add an `LICENSE` file in the repository if required.
