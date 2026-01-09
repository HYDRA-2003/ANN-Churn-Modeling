# ANN-Churn-Modeling

# 🧠 Customer Churn Prediction Web Application
This project is a Streamlit-based web application designed to predict customer churn using a trained machine learning model. The application allows users to input their data, which is then preprocessed and used to make predictions based on a set of input features, including geography, gender, age, balance, credit score, and others. The core features of the project include data preprocessing, model training, and prediction, making it a comprehensive solution for customer churn prediction.

## 🚀 Features
- **Data Preprocessing**: The application uses scikit-learn's LabelEncoder, OneHotEncoder, and StandardScaler to preprocess user input data.
- **Model Training**: The project includes a Jupyter Notebook file for training a machine learning model using TensorFlow and scikit-learn.
- **Prediction**: The application makes predictions based on user input data using the trained model.
- **User Interface**: The application has a user-friendly interface built with Streamlit, allowing users to input their data and view the prediction results.
- **Example Use Cases**: The project includes example use cases in the form of Jupyter Notebook files for testing and validating the model.

## 🛠️ Tech Stack
- **Frontend**: Streamlit
- **Backend**: Python
- **Machine Learning**: TensorFlow, scikit-learn
- **Data Manipulation**: pandas, numpy
- **Dependencies**: tensorboard, matplotlib, scikeras
- **Package Manager**: pip

## 📦 Installation
To install the required dependencies, run the following command:
```bash
pip install -r requirements.txt
```
This will install all the necessary libraries and their versions specified in the requirements.txt file.

## 💻 Usage
1. **Prerequisites**: Install the required dependencies using pip.
2. **Running the Application**: Run the application using the following command:
```bash
streamlit run app.py
```
This will start the Streamlit server and open the application in your default web browser.
3. **Testing and Validation**: Use the Jupyter Notebook files to test and validate the model.

## 📂 Project Structure
```markdown
.
├── app.py
├── experiments.ipynb
├── prediction.ipynb
├── requirements.txt
└── README.md
```


## 🤝 Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.


A huge thanks to everyone who has contributed to this project! Your support and contributions are greatly appreciated.

This is written by [readme.ai](https://readme-generator-phi.vercel.app/)
