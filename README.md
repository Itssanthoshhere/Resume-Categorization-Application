# Resume Categorization Application

![Resume Categorization Application](https://via.placeholder.com/800x200.png?text=Resume+Categorization+Application)
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

For any questions or feedback, feel free to reach out via [santhosh02vs@gmail.com](santhosh02vs@gmail.com).
