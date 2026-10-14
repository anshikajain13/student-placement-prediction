# Student Placement Prediction Using Decision Tree

## About the Project

This project is a Machine Learning application that predicts student placement outcomes using a Decision Tree classifier. It provides a web interface built with FastAPI where users can enter student-related details and receive a prediction.

## Features

- Machine Learning prediction using a Decision Tree model
- FastAPI-based web application
- HTML form for user input
- Saved model for making predictions
- API documentation through FastAPI Swagger UI

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- FastAPI
- Uvicorn
- Joblib
- HTML
- Jinja2

## Project Structure

```text
student-placement-prediction/
├── app.py
├── Decision_Tree.ipynb
├── placement_model.joblib
├── columns.joblib
├── student_performance_dataset.csv
├── requirements.txt
├── .gitignore
└── templates/
    └── index.html
```

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/anshikajain13/student-placement-prediction.git
cd student-placement-prediction
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

**Windows Command Prompt:**

```cmd
venv\Scripts\activate.bat
```

### 4. Install dependencies

```bash
python -m pip install -r requirements.txt
```

## Run the Application

Start the FastAPI server:

```bash
python -m uvicorn app:app --reload
```

Open the application in your browser:

- Homepage: http://127.0.0.1:8000
- API documentation: http://127.0.0.1:8000/docs

## Machine Learning Workflow

1. Load and explore the student performance dataset.
2. Prepare the data for model training.
3. Train a Decision Tree classifier.
4. Save the trained model and required column information.
5. Load the saved files in the FastAPI application.
6. Enter student details through the web interface and view the prediction.

## Future Improvements

- Evaluate the model using suitable classification metrics.
- Improve input validation and error handling.
- Deploy the application online.
- Enhance the user interface.

## Author

**Anshika Jain**

GitHub: https://github.com/anshikajain13