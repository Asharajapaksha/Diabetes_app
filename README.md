Check Your Diabetes Level
Description
This Streamlit app allows users to check their diabetes status based on various health parameters. The app predicts whether a person is diabetic or not using a machine learning model (Random Forest Classifier) trained on the Pima Indians Diabetes Database.

Features
User Input: Allows users to input their health data (e.g., Pregnancies, Glucose, Blood Pressure, etc.) through sliders on the sidebar.
Patient Data Visualization: Visualizes the user's input data against the training data for various parameters like Age, Glucose, Blood Pressure, and more.
Diabetes Prediction: Predicts if the user is diabetic based on the input data.
Training Data Statistics: Displays the summary statistics of the training dataset.
Upload Image and Video Display: Allows users to upload their photos and displays a video related to diabetes.
Requirements
Python 3.x
Streamlit
Pandas
Numpy
Matplotlib
Seaborn
Plotly
Scikit-learn
PIL (Pillow)
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your_username/diabetes-prediction-app.git
cd diabetes-prediction-app
Install the required packages:
bash
Copy code
pip install -r requirements.txt
How to Run the App
Navigate to the project directory.
Run the Streamlit app:
bash
Copy code
streamlit run app.py
The app will open in your default web browser.
Files
app.py: Main Python script containing the code for the Streamlit app.
diabetes.csv: The dataset used for training the model.
Diabetesimage.png: Image displayed in the app.
Diabetesvideo.mp4: Video displayed in the app.
requirements.txt: List of required Python packages.
Dataset
The dataset used in this app is the Pima Indians Diabetes Database, which contains data on 768 female patients of Pima Indian heritage. The dataset includes health-related variables such as glucose level, insulin level, BMI, and more.

Model
The app uses a Random Forest Classifier to predict the diabetes outcome based on user input. The model is trained on the Pima Indians Diabetes Database.

Accuracy
The model's accuracy is displayed in the app after the prediction. The accuracy score is calculated on the test set after splitting the data into training and testing sets.
