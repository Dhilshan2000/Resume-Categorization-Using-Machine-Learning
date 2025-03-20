## Resume Categorization Using Python

This project is a Python-based application that automates the process of categorizing resumes using machine learning and natural language processing (NLP) techniques. It processes uploaded PDF resumes and classifies them into predefined job categories like "Python Developer," "HR," "Data Science," and more.

### Features

- Automatic Resume Categorization: Automatically categorizes resumes into job categories using machine learning models.
- Text Preprocessing: Cleans and processes the text from resumes using regular expressions and NLP techniques.
- Model Integration: Uses a pre-trained machine learning model for text classification to predict the category of each resume.
- Organized Output: Categorized resumes are saved in separate folders based on predicted job roles.
- CSV Output: A CSV file with the categorized resumes' details can be downloaded for further processing.

### How It Works

- Upload Resumes: The application accepts PDF resume files.
- Text Cleaning: The text from the resumes is extracted and cleaned (removes URLs, special characters, etc.).
- Prediction: The cleaned text is then passed through a pre-trained machine learning model that predicts the job category.
- Categorization: Resumes are saved into categorized folders based on the prediction.
- Results: The categorized data is displayed and can be downloaded as a CSV file.

### Requirements

- Python 3.x
- Streamlit
- scikit-learn
- pandas
- pypdf
- pickle
- Project Structure
- graphql

[Resume_Categorizer_WebApp](https://github.com/user-attachments/assets/752014d9-d0ed-43b2-b160-9f95b523a071)

[Resume_Categorizer_WebApp_Result](https://github.com/user-attachments/assets/b0c34a4e-d416-49b5-a8e0-af69ae48dd55)



