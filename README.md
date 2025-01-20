# AI-Powered Resume Analyzer

The AI-Powered Resume Analyzer is a tool designed to analyze, score, and optimize resumes for ATS (Applicant Tracking System) compatibility and job-specific relevance. Built using **Python 3.8**, the tool leverages **NLP**, **Streamlit**, and various Python libraries to provide actionable insights for job seekers and recruiters.

---

## Features

- Analyze resumes for role-specific relevance and skills.
- Extract key information like education, skills, and work experience using NLP.
- Provide real-time suggestions to improve resume quality.
- User-friendly interface built with Streamlit.

---

## Prerequisites

- Python 3.8.0 (or compatible version)
- Ensure `pip` is installed and up to date.

---

## Project Structure

```plaintext
├── Logo/                # Contains the project logo
├── Uploaded_Resumes/    # Directory for uploaded resumes
├── __pycache__/         # Python cache files
├── .gitattributes       # Git configuration file
├── App.py               # Main application script
├── Courses.py           # Course recommendations module
├── python-3.8.0-amd64.exe # Python installer
├── README.md            # Project documentation
├── requirements.txt     # Dependencies file
```

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ashwii30/AI-Powered-Resume-Analyzer
   cd Resume-Analyzer
   ```

2. Install Python 3.8.0:
   If Python 3.8 is not installed, you can use the provided `python-3.8.0-amd64.exe` installer or download it from the official [Python website](https://www.python.org/).

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Download the **spaCy English model**:
   ```bash
   python -m spacy download en_core_web_sm
   ```

---

## Usage

1. Run the application:
   ```bash
   streamlit run App.py
   ```

2. Open your browser and navigate to:
   ```plaintext
   http://localhost:8501
   ```

3. Upload a resume in PDF format and follow the instructions on the interface.

---

## Dependencies

The project uses the following Python libraries:

- `pandas` - Data manipulation and analysis.
- `spacy==2.3.5` - Natural Language Processing.
- `streamlit` - Web application framework.
- `plotly` - Data visualization.
- `pymysql` - MySQL database connector.
- `streamlit-tags` - Streamlit extension for tag input.
- `Pillow` - Image processing.
- `nltk` - Natural Language Toolkit.
- `pdfminer3` - PDF parsing.
- `yt_dlp` - YouTube content parsing.
- `pyresparser` - Resume parsing.

Install all dependencies using:
```bash
pip install -r requirements.txt
```

---

## Directory Usage

- **Logo/**: Store the project logo.
- **Uploaded_Resumes/**: All uploaded resumes are stored in this folder.
- **App.py**: Main script to run the Streamlit application.

---

## Contribution

Feel free to submit pull requests or open issues to improve the tool. Contributions are welcome!

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

Special thanks to the developers of **spaCy**, **Streamlit**, and other libraries used in this project for making development seamless.