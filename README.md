# Phishing-detection-system

This is my mini project on phishing detection using Machine Learning.
It can detect:
- Fake / phishing websites (using URL)
- Phishing emails (using text)


##  What I used
- Python
- FastAPI
- XGBoost (ML model)
- TF-IDF (for text conversion)
- LIME (to explain predictions)
- HTML, CSS, JavaScript
- Chrome Extension

##  How it works
1. User enters a URL or email text  
2. Data is converted into numerical form using TF-IDF  
3. Model predicts whether it is Safe or Phishing  
4. Result is shown with confidence score  
5. LIME shows why the model gave that result  


## Chrome Extension
- Checks current website URL  
- Alerts if phishing detected  
- Can scan email content (like Gmail)  


## How to run
Install dependencies:

