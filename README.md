# Heart-Disease-Prediction
Heart Disease Classification Web App 🩺


This project is a web-based application built using Streamlit that classifies the likelihood of heart disease based on medical parameters. It takes user inputs such as age, cholesterol levels, chest pain type, and other health indicators to predict whether the person is likely to have heart disease or not.

Features
User-friendly web interface to input medical report details.
Predicts whether a person is at risk of heart disease.
Uses pre-trained machine learning model for classification.
How It Works
The user inputs their medical report details, such as age, sex, chest pain type, blood pressure, cholesterol, heart rate, and other relevant features.
The app scales the inputs using a pre-trained scaler and uses a machine-learning model to predict whether the person has heart disease.
Based on the input, the app displays whether the user is fit or needs treatment.
Model
The app uses a pre-trained classification model stored in a .pkl file.
It also uses a pre-trained scaler to normalize the input features before prediction.
Installation and Usage
Clone the repository:
git clone "https://github.com/More-Sushant/Heart-Disease-Classification.git"
Navigate to the project directory:
cd heart-disease-classification
Install the required packages:
pip install -r requirements.txt
Place the pre-trained model files (Model.pkl and scaler.pkl) in the ./models/ directory.

Run the Streamlit app:

streamlit run app.py
Open your browser and go to http://localhost:8501 to access the app.
Optional way -->
Download the files and extract them.
Open the terminal or anaconda prompt at the same location and fulfill the required library in a particular environment.
Type "streamlit run app.py" in that terminal.
A web page will open to enter details.
Enter the value of the specified parameters.
Click on the predict button to generate results.
Input Parameters
The following inputs are required for prediction:

Age: Age of the patient.
Sex: Gender (0 for Female, 1 for Male).
Chest Pain Type:
1: Typical angina
2: Atypical angina
3: Non-anginal pain
4: Asymptomatic
Resting Blood Pressure (trestbps): Blood pressure level (in mm Hg).
Cholesterol (chol): Serum cholesterol level (in mg/dl).
Resting ECG (restecg):
0: Normal
1: ST-T wave abnormality or Left Ventricular Hypertrophy (enlarged heart)
Max Heart Rate Achieved (thalach): Maximum heart rate achieved during exercise.
Exercise-Induced Angina (exang):
0: No
1: Yes
Oldpeak: Depression induced by exercise relative to rest.
Slope of the Peak Exercise ST Segment (slope):
1: Upsloping
2: Flat
3: Downsloping
Number of Major Vessels (ca): Number of coronary arteries with significant stenosis.
Thalassemia (thal):
1: Normal
2: Fixed defect
3: Reversible defect
Project Structure
.
├── app.py                  # Main Streamlit app script
├── models/
│   ├── Model.pkl           # Pre-trained heart disease classification model
│   └── scaler.pkl          # Pre-trained scaler for input normalization
├── modules/
│   └── heartDisease.ipynb  # Python file for selection of model
├── requirements.txt        # List of required Python packages
└── README.md               # Project documentation
Requirements
Python 3.x
Streamlit
Pandas
Scikit-learn
Pickle
You can install the necessary dependencies using the requirements.txt file provided in the repository.

Acknowledgements
The dataset used to train the model is from UCI Heart Disease Dataset.
Scikit-learn is used for building and training the model.
Streamlit is used for the web interface.
License
This project is licensed under the MIT License.

Upvote, Share and follow for more⬆️⬆️⬆️🔝.

Made with ❤️ by Sushant
