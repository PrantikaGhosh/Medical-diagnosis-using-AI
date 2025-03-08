# Medical Disease Prediction using Machine Learning

## Table of Contents
- [Cloning the Repository](#cloning-the-repository)
- [Setting Up the Virtual Environment](#setting-up-the-virtual-environment)
- [Installing Dependencies](#installing-dependencies)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)

## Cloning the Repository
First, clone this repository using the following command:

```bash
git clone https://github.com/your-username/your-repo.git](https://github.com/PrantikaGhosh/Medical-diagnosis-using-AI.git
cd Medical-diagnosis-using-AI
```

## Setting Up the Virtual Environment
Create a virtual environment to manage dependencies:

```bash
python -m venv venv
```

Activate the virtual environment:
- On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```
- On Windows:
  ```bash
  venv\Scripts\activate
  ```

## Installing Dependencies
Once the virtual environment is activated, install the required dependencies:

```bash
pip install -r requirements.txt
```

## Running the Application
Run the Streamlit web application using the following command:

```bash
streamlit run app.py
```

This will start a local server, and you can access the web app in your browser.

## Project Structure
```
📂 Medical-diagnosis-using-AI
├── 📂 Datasets             # Folder containing datasets
├── 📂 Models               # Folder containing trained models
├── .gitignore             # Git ignore file
├── Heart_Disease_Prediction.ipynb  # Jupyter Notebook for heart disease prediction
├── Lung_Cancer.ipynb      # Jupyter Notebook for lung cancer prediction
├── Parkinson's_Disease_Detection.ipynb # Jupyter Notebook for Parkinson’s disease detection
├── README.md              # Project documentation
├── Thyroid.ipynb          # Jupyter Notebook for thyroid disease prediction
├── app.py                 # Streamlit web application
├── requirements.txt       # List of required dependencies
```
