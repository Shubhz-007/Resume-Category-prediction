# Resume-Category-Prediction

This Python application utilizes **Machine Learning** to classify resumes into categories based on their content. It features text extraction from uploaded resumes in PDF, DOCX, or TXT formats, preprocessing, and prediction using a pre-trained model.

## Features
- **File Upload**: Supports PDF, DOCX, and TXT formats.
- **Text Extraction**: Extracts and cleans resume content.
- **Resume Categorization**: Uses ML models for predicting job categories.
- **Interactive Interface**: Built with Streamlit for ease of use.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/resume-screening-app.git
   cd resume-screening-app
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Place pre-trained `clf.pkl`, `tfidf.pkl`, and `encoder.pkl` files in the project directory.

## Usage
Run the application locally:
```bash
streamlit run app.py
```

Upload a resume and get the predicted job category.

## Dependencies
- Python
- Streamlit
- PyPDF2
- python-docx
- scikit-learn
- re (standard library)

## Future Enhancements
- Add support for more file formats.
- Improve model performance with additional training data.

## clf.pkl file is not uploaded in the repo due to size constraint. Running the .ipynb file beforehand creates the file itself.
