# Automatic Text Summarization for Visually Impaired Individuals Using NLP

An NLP-based project that summarizes long text content into concise and meaningful summaries to make information easier to access for visually impaired individuals.

---

## Project Overview

The goal of this project is to build an automatic text summarization system that reduces lengthy text into shorter summaries while preserving the main meaning. This project can help visually impaired users consume information more efficiently by reducing reading or screen-reader time.

This project covers:

- Text Preprocessing
- Natural Language Processing
- Text Summarization
- Summary Generation
- Accessibility-Focused Application

---

## Features

- Summarizes long text into concise output
- Uses NLP techniques for text processing
- Helps reduce reading time for visually impaired individuals
- Supports accessibility-focused use cases
- Beginner-friendly NLP project structure

---

## Tech Stack

### Languages and Tools

- Python
- Jupyter Notebook / Python Script

### Libraries Used

- NLTK
- spaCy
- Scikit-learn
- Pandas
- NumPy

---

## Project Structure

```bash
Automatic-Text-Summarization-for-Visually-Impaired-Individuals-Using-NLP/
│
├── data/                     # Input text datasets
├── notebooks/                # Jupyter notebooks
├── src/                      # Source code files
├── app.py                    # Main application file
├── requirements.txt          # Dependencies
└── README.md                 # Project documentation
```

---

## Workflow

### 1. Input Text

The system accepts long text content from sources such as:

- Articles
- Documents
- Notes
- Paragraphs
- Web content

### 2. Text Preprocessing

The input text is cleaned and prepared using NLP preprocessing steps:

- Lowercasing
- Tokenization
- Stopword removal
- Punctuation removal
- Sentence segmentation

### 3. Feature Extraction

Important text features are extracted to identify key sentences and meaningful information.

Common techniques include:

- Word frequency analysis
- Sentence scoring
- TF-IDF vectorization

### 4. Summary Generation

The system selects the most important sentences and generates a concise summary that preserves the original meaning.

### 5. Accessibility Support

The generated summary can be used with screen readers or text-to-speech systems to make content easier to consume for visually impaired individuals.

---

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Javed3010/Automatic-Text-Summarization-for-Visually-Impaired-Individuals-Using-NLP.git
cd Automatic-Text-Summarization-for-Visually-Impaired-Individuals-Using-NLP
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

### 3. Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Mac/Linux

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Project

### Using Python Script

```bash
python app.py
```

### Using Jupyter Notebook

```bash
jupyter notebook
```

---

## Sample Output

```bash
Input Text:
Artificial Intelligence is transforming the way people interact with technology. It helps automate tasks, analyze data, and improve accessibility for people with disabilities.

Generated Summary:
Artificial Intelligence improves accessibility and helps automate tasks.
```

---

## Future Improvements

- Add text-to-speech support
- Add OCR support for scanned documents
- Create a web interface using Flask or Streamlit
- Support multiple languages
- Improve summary quality using transformer models
- Deploy on Render, Heroku, or Streamlit Cloud

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## License

This project is licensed under the MIT License.

---

## Author

Mohamed Javed Khan

- GitHub: https://github.com/Javed3010
- Project Repository: https://github.com/Javed3010/Automatic-Text-Summarization-for-Visually-Impaired-Individuals-Using-NLP

---
