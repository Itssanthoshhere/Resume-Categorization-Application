# Resume Categorization Application

![Resume Categorization Application](https://via.placeholder.com/1000x100.png?text=Resume+Categorization+Application)
![Resume Categorization Application](https://github.com/Itssanthoshhere/Resume-Categorization-Application/blob/main/Sample%20Interface.png?raw=true)

## Overview

The **Resume Categorization Application** is a machine learning-powered tool designed to categorize resumes based on their content. Built using Python and Streamlit, this application provides an interactive user interface that allows users to upload multiple PDF resumes, which are then processed and categorized into relevant job roles.

## Features

- **Upload Resumes**: Users can upload multiple PDF files containing resumes for categorization.
- **Categorization**: Each resume is analyzed and classified into predefined job categories such as Java Developer, Python Developer, Data Science, etc.
- **Download Results**: Users can download a summary of categorized results as a CSV file.
- **User-Friendly Interface**: Built with Streamlit, providing a seamless experience for users.

## Technologies Used

- **Python**: The primary programming language used for development.
- **Streamlit**: A framework for building web applications in Python.
- **pandas**: A data manipulation library used for handling dataframes.
- **pypdf**: A library for reading PDF files to extract text.
- **scikit-learn**: A machine learning library used for model training and prediction.
- **Pickle**: For serializing and deserializing Python objects.

## Installation

Follow these steps to set up the application on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Resume_Categorization_Application.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd Resume_Categorization_Application
   ```

3. **Install Required Libraries**:
   It is recommended to use a virtual environment. If you haven't set one up, you can do so with the following commands:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
   Then, install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   Start the Streamlit application using the following command:
   ```bash
   streamlit run app.py
   ```

5. **Access the Application**:
   Open your web browser and go to `http://localhost:8501` to access the application.

## Usage

1. **Upload PDF Files**: Click on the "Choose PDF files" button to upload resumes.
2. **Specify Output Directory**: Provide a directory where categorized resumes will be saved.
3. **Categorize Resumes**: Click the "Categorize Resumes" button to start the categorization process.
4. **Download Results**: Once the categorization is complete, download the results as a CSV file for further analysis.

## Model Information

The application uses a pre-trained machine learning model to categorize resumes. The model is trained on a labeled dataset, and predictions are made based on features extracted from the resumes.

### Category Mapping

The following job categories are used in the application:
- Java Developer
- Python Developer
- Data Science
- Web Designing
- DevOps Engineer
- Testing
- HR
- Mechanical Engineer
- And more...

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please feel free to open an issue or submit a pull request.

### Steps to Contribute
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## Acknowledgments

- [Streamlit](https://streamlit.io) for the framework used to build the web application.
- [pandas](https://pandas.pydata.org) for data manipulation.
- [pypdf](https://pypdf2.readthedocs.io/en/latest/) for PDF text extraction.
- [scikit-learn](https://scikit-learn.org) for machine learning functionalities.
  
## 🔗 Connect with Me
- **LinkedIn:** [Santhosh VS](https://www.linkedin.com/in/thesanthoshvs/)
- **GitHub:** [Itssanthoshhere](https://github.com/Itssanthoshhere)

For any questions or feedback, feel free to reach out via [santhosh02vs@gmail.com](santhosh02vs@gmail.com).





# 📄 Resume Categorization Application

![Resume Categorization Application](https://github.com/yourusername/Resume_Categorization_Application/blob/main/resume_categorization.png)

## 🚀 Overview

Welcome to the **Resume Categorization Application**! This application leverages Python and machine learning to automatically categorize resumes based on their content. It’s designed to streamline the recruitment process, making it easier for hiring managers to manage and sort through applicants.

### 🌟 Features

- **Upload Multiple Resumes**: Easily upload PDF resumes for categorization.
- **Automated Classification**: Utilizes a trained machine learning model to categorize resumes into predefined job categories.
- **Downloadable Results**: Download the categorization results in a convenient CSV format.
- **Clean and Intuitive Interface**: Built with Streamlit for a seamless user experience.

### ⚙️ How It Works

1. **Upload**: Choose one or more PDF resumes using the file uploader.
2. **Process**: The application reads each resume, cleans the text, and applies the machine learning model to predict the category.
3. **Categorize**: Resumes are sorted into folders based on their predicted job category.
4. **Download**: Get a CSV file containing the results of the categorization.

## 📦 Installation

To run this application locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Resume_Categorization_Application.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd Resume_Categorization_Application
   ```
3. **Install Required Packages**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

## 🛠️ Technologies Used

- **Python**: The core programming language.
- **Streamlit**: For building the web application interface.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For machine learning functionalities.
- **PyPDF2**: For reading PDF files.

## 🎯 Use Cases

- **HR Departments**: Simplify the resume sorting process.
- **Recruitment Agencies**: Enhance the speed and accuracy of candidate assessments.
- **Job Seekers**: Understand the skill sets and requirements for various job categories.

## 💡 Contributing

We welcome contributions! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

## 📞 Contact

For any inquiries or support, please reach out to [your email or GitHub profile link].
