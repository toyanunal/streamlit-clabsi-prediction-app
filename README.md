# Central Line-Associated Bloodstream Infections (CLABSI) Prediction App

## Description
This Streamlit application uses a pretrained GradientBoostingClassifier to predict the likelihood of Central Line-Associated Bloodstream Infections (CLABSI) in patients. The prediction is based on various inputs gathered during the first 24 hours of hospitalization. This tool is designed to assist health professionals in identifying high-risk patients early and improving clinical outcomes.

## Deployed Application
* [https://clabsi-prediction-model.streamlit.app/](https://clabsi-prediction-model.streamlit.app/)

## Technologies Used
* VSCode (as text editor)
* Chrome (as web browser)
* Python (as programming language)
* Streamlit (as framework)
* Pandas (for data manipulation)
* Pickle (for model serialization)
* GradientBoostingClassifier (from scikit-learn for machine learning)

## Installation

### Prerequisites
* Python 3.6 or higher
* pip (Python package installer)

### Setup
1. Navigate to your projects directory.
2. Clone the repository and install the required packages:
    ```sh
    git clone https://github.com/toyanunal/streamlit-clabsi-prediction-app.git
    cd streamlit-clabsi-prediction-app
    pip install -r requirements.txt
    ```

## Usage
1. Run the application:
    ```sh
    streamlit run streamlit_app.py
    ```

2. Open your web browser and go to `http://localhost:8501` to access the app.

## Screenshots
### Home page
![image](https://github.com/toyanunal/streamlit-clabsi-prediction-app/assets/59750131/58ec45db-168c-402f-9330-d170deb695cc)
