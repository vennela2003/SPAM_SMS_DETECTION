# SPAM_SMS_DETECTION

This project implements a machine-learning based SMS spam detection system using Streamlit, NLTK, and scikit-learn.

## Requirements

To run this project, you need to have the following dependencies installed:

1. Streamlit
2. NLTK (Natural Language Toolkit)
3. scikit-learn

You can install these dependencies using pip:

bash
pip install streamlit nltk scikit-learn

To Setup:
mkdir -p ~/.streamlit/
echo "\
[server]\n\
port = $PORT\n\
enableCORS = false\n\
headless = true\n\
\n\
" > ~/.streamlit/config.toml

Usage
To run the SMS spam detection system, execute the following command:

bash
Copy code
streamlit run sms_spam_detection.py
Once the Streamlit server is running, you can access the application in your web browser.

vbnet
Copy code

This readme provides a brief overview of the project, lists the required dependencies, and gives instructions on how to run the SMS spam detection system using Streamlit.
