# Resume Categorization Application

![Resume Categorization Application](https://via.placeholder.com/1000x100.png?text=Resume+Categorization+Application)
![Resume Categorization Application](https://github.com/Itssanthoshhere/Resume-Categorization-Application/blob/main/Sample%20Interface.png?raw=true)

## 📋 Overview  

The **Resume Categorization Application** is a Python-based solution powered by Machine Learning to classify resumes into predefined job categories. It offers a simple yet efficient interface built with **Streamlit** for uploading, categorizing, and organizing resumes in just a few clicks.

### ✨ Key Features  
- **Resume Upload**: Accepts multiple PDF files for processing.  
- **Categorization**: Analyzes resume content to predict job roles like Java Developer, Data Scientist, etc.  
- **Result Export**: Outputs categorized results in a downloadable CSV format.  
- **Interactive Interface**: A clean and user-friendly interface for a seamless experience.

---

## 🛠️ Technologies Used  

| **Category**       | **Technologies**                                                                 |
|---------------------|----------------------------------------------------------------------------------|
| Programming Language| Python                                                                          |
| Framework           | Streamlit                                                                      |
| Libraries           | `pandas`, `pypdf`, `nltk`, `scikit-learn`, `Pickle`                             |
| ML Techniques       | NLP (Text Cleaning, TF-IDF Vectorization), Logistic Regression, SVM, Naive Bayes|

---

## 🚀 Installation  

Follow these steps to set up the application:  

### 1. Clone the Repository  
```bash
git clone https://github.com/Itssanthoshhere/Resume-Categorization-Application.git
cd Resume-Categorization-Application
```

### 2. Create and Activate Virtual Environment  
```bash
python -m venv venv
source venv/bin/activate    # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies  
```bash
pip install -r requirements.txt
```

### 4. Run the Application  
```bash
streamlit run app.py
```

---

## ⚙️ How It Works  

### **Step-by-Step Guide**  
1. **Upload Resumes**: Upload multiple PDF resumes via the interface.  
2. **Process Resumes**: Click on "Categorize Resumes" to analyze the content.  
3. **Categorization**: Resumes are classified into roles like Java Developer, Python Developer, Data Scientist, etc.  
4. **Download Results**: Save results as a CSV for further analysis.  

---

## 💻 Code Highlights  

### **Text Preprocessing**  
Removes URLs, special characters, and unwanted spaces to clean the resume content.  
```python
import re

def clean_resume(text):
    text = re.sub('http\S+', ' ', text)
    text = re.sub('[^A-Za-z0-9]+', ' ', text)
    return text.lower().strip()
```

### **Machine Learning Model Loading**  
Pre-trained models and vectorizers are loaded using Pickle for efficient predictions.  
```python
import pickle

with open('vectorizer.pkl', 'rb') as vec_file:
    vectorizer = pickle.load(vec_file)

with open('model.pkl', 'rb') as model_file:
    model = pickle.load(model_file)
```

### **Streamlit Interface**  
Interactive interface for file upload and result display.  
```python
import streamlit as st

st.title("Resume Categorization Application")
uploaded_files = st.file_uploader("Upload Resumes (PDF)", type="pdf", accept_multiple_files=True)
if st.button("Categorize Resumes"):
    results = categorize_resumes(uploaded_files)
    st.write(results)
```

---

## 🎯 Applications  

This application can be used in various domains:  

- **Recruitment Agencies**: Automate resume classification for faster candidate evaluation.  
- **HR Teams**: Organize large volumes of resumes with minimal effort.  
- **Job Portals**: Provide categorization tools for users uploading resumes.  

---

## 📊 Model and Categories  

### **Categories**  
Resumes are classified into the following job roles:  
- Java Developer  
- Python Developer  
- Data Scientist  
- Web Developer  
- DevOps Engineer  
- Testing Engineer  
- HR  
- Mechanical Engineer  

### **Model Overview**  
The ML model is trained on a labeled dataset using:  
- **Text Features**: Extracted using TF-IDF vectorization.  
- **Classification Algorithms**: Logistic Regression, SVM, Naive Bayes, etc.  

---

## 📦 Folder Structure  

```
Resume-Categorization-Application/
│
├── .ipynb_checkpoints/           # Jupyter Notebook checkpoints
├── Resume Data For Testing/      # Sample resume PDFs for testing
├── categorized_resumes/          # Folder to save categorized resumes
├── Dataset - Resume.csv          # Dataset used for training the model
├── README.md                     # Project documentation
├── Resume Categorization using Python.ipynb # Jupyter Notebook with the workflow
├── Sample Interface.png          # Screenshot of the application
├── app.py                        # Main application file
├── model.pkl                     # Trained ML model
├── test.py                       # Unit tests for the application
```

--- 

## 🏗️ Contributing  

Contributions are welcome! Here's how you can help:  

1. Fork the repository.  
2. Create a new branch for your feature (`git checkout -b feature-name`).  
3. Make your changes and commit them (`git commit -m "Add feature"`)  
4. Push your branch (`git push origin feature-name`)  
5. Open a pull request.  

---

## 🙏 Acknowledgments  

- **[Streamlit](https://streamlit.io)** for the web application framework.  
- **[scikit-learn](https://scikit-learn.org)** for machine learning capabilities.  
- **[pandas](https://pandas.pydata.org)** for data handling.  
- **[pypdf2](https://pypdf2.readthedocs.io)** for PDF text extraction.  

---

## 🔗 Connect with Me
- **LinkedIn:** [Santhosh VS](https://www.linkedin.com/in/thesanthoshvs/)
- **GitHub:** [Itssanthoshhere](https://github.com/Itssanthoshhere)

## 📞 Contact

For any questions or feedback, feel free to reach out via [santhosh02vs@gmail.com](santhosh02vs@gmail.com).
