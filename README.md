Profanity Detection & Censorship using Machine Learning  

Overview  
This project uses Logistic Regression with TF-IDF vectorization to detect and censor profane words in text comments.  

Features  
- Detects profanity and classifies text as profane or non-profane.  
- Censors offensive words using the `better_profanity` library.  
- Machine learning model trained using TF-IDF and Logistic Regression.  
- Evaluation metrics provided through a classification report.  

Dataset  
Input: `profanity_dataset.xlsx` (must contain `Text` and `Label` columns).  
Processing: Converts text into TF-IDF vectors for classification.  
 
Installation  
Run the following command to install dependencies:  

pip install pandas scikit-learn better_profanity openpyxl


Usage  
1. Prepare the dataset by ensuring `profanity_dataset.xlsx` has labeled text.  
2. Run the script:  

   python profanity_detection.py

3. Enter a comment for analysis.  
4. Output includes:  
   - Censored text  
   - Predicted class (Profane/Non-Profane)  

Model Training & Evaluation  
Vectorization: Uses TF-IDF (`TfidfVectorizer`) to extract features.  
Algorithm:Logistic Regression for text classification.  
Performance: Evaluated using a classification report.  

Future Improvements  
- Use deep learning (LSTMs/BERT) for better accuracy.  
- Implement real-time API for profanity filtering.  
- Support multi-language detection.  


Installation
Clone the repository:

   git clone https://github.com/Nithyasriperiasamy/ProfanityFilter.git
