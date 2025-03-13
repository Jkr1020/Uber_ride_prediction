# Uber_ride_prediction

## Description
This project predicts the number of weekly rides using machine learning. It utilizes a trained model to estimate demand based on input features.

## Features
- Flask-based web application for prediction.
- Machine learning model trained using Scikit-learn.
- Simple UI for users to input data and get predictions.

## Project Structure
```
├── app.py             # Flask application for model inference
├── MLmodel.ipynb      # Jupyter notebook for training the model
├── model.pkl         # Serialized trained model
├── pyproject.toml    # Project dependencies and configuration
├── poetry.lock       # Dependency lock file
├── taxi.csv          # Dataset used for training
├── templates/
│   ├── index.html    # Web interface
```

## Installation

### Prerequisites
- Python 3.12+
- Poetry (for dependency management)

### Steps
1. **Clone the repository**  
   ```
   git clone <repo-url>
   cd uber-project
   ```

2. **Install dependencies**  
   ```
   poetry install
   ```

3. **Run the Flask App**  
   ```
   poetry run python app.py
   ```
   The app will be available at `http://127.0.0.1:5000/`

## Usage
- Open the web app in a browser.
- Enter the required input values.
- Click the "Predict" button to get the estimated weekly rides.

## Model Training
- The `MLmodel.ipynb` contains the Jupyter Notebook for training the model.
- The dataset (`taxi.csv`) is used to train a regression model using Scikit-learn.
- The trained model is saved as `model.pkl`.

## Dependencies
This project requires the following dependencies (managed via `pyproject.toml`):
- Flask
- NumPy
- Pandas
- Scikit-learn
- IPykernel

## License
This project is for educational purposes.

---
Developed by **Kishore Ram J**

