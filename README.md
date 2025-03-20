Resume Categorization Using Python
This project is a Python-based application that automates the process of categorizing resumes using machine learning and natural language processing (NLP) techniques. It processes uploaded PDF resumes and classifies them into predefined job categories like "Python Developer," "HR," "Data Science," and more.

Features
Automatic Resume Categorization: Automatically categorizes resumes into job categories using machine learning models.
Text Preprocessing: Cleans and processes the text from resumes using regular expressions and NLP techniques.
Model Integration: Uses a pre-trained machine learning model for text classification to predict the category of each resume.
Organized Output: Categorized resumes are saved in separate folders based on predicted job roles.
CSV Output: A CSV file with the categorized resumes' details can be downloaded for further processing.
How It Works
Upload Resumes: The application accepts PDF resume files.
Text Cleaning: The text from the resumes is extracted and cleaned (removes URLs, special characters, etc.).
Prediction: The cleaned text is then passed through a pre-trained machine learning model that predicts the job category.
Categorization: Resumes are saved into categorized folders based on the prediction.
Results: The categorized data is displayed and can be downloaded as a CSV file.
Installation
To run this project locally, follow the steps below.

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/resume-categorization.git
cd resume-categorization
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the app:

bash
Copy code
streamlit run app.py
This will start a Streamlit app where you can upload resumes for categorization.

Requirements
Python 3.x
Streamlit
scikit-learn
pandas
pypdf
pickle
Project Structure
graphql
Copy code
.
├── app.py                   # Main Streamlit app file
├── tfidf.pkl                # Pre-trained TF-IDF vectorizer model
├── model.pkl                # Pre-trained machine learning model
├── requirements.txt         # List of required Python packages
├── categorized_resumes/      # Folder where categorized resumes will be saved
└── README.md                # This README file
How to Use
Launch the app with the command:

bash
Copy code
streamlit run app.py
Upload PDF resumes via the file uploader on the Streamlit interface.

Choose an output directory where the categorized resumes will be saved.

Click the "Categorize Resumes" button to process the files.

Once the categorization is complete, download the results as a CSV file.

What I Learned
The application helped me deepen my understanding of Natural Language Processing (NLP) and machine learning for text classification.
I learned how to clean and preprocess text data using Python's regex and NLP libraries.
Hands-on experience with machine learning models for real-world applications in HR and recruitment.
Future Improvements
Improved Model: Fine-tune the machine learning model for better accuracy.
File Format Support: Extend the support to other file formats like Word documents.
User Interface: Enhance the Streamlit UI for better user experience.
