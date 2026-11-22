# SMS Spam Detection Using Python

## Project Overview
SMS Spam Detection is a Python-based project that identifies whether a text message is Spam or Ham (Not Spam). It uses a rule-based classification approach to analyze message content and detect suspicious patterns.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** pandas, Regular Expressions, scikit-learn
- **Backend:** Flask
- **Interface:** HTML, CSS

## Key Features
- Detects spam and legitimate SMS messages.
- Uses keyword-based rule classification.
- Identifies suspicious links and promotional messages.
- Calculates a spam score based on message indicators.
- Displays prediction results through a Flask web interface.
- Evaluates predictions using classification metrics.

## Classification Indicators
The system checks seven indicator groups:
1. Prize-related messages
2. Promotional content
3. Urgency-related words
4. Money-related terms
5. Suspicious links
6. Call-to-claim messages
7. Opt-out indicators

## Dataset
The project uses a labelled SMS dataset containing spam and legitimate messages.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

## Installation and Setup

1. Clone or download this repository.
2. Open the project folder in VS Code.
3. Install the required dependencies:

```bash
pip install pandas scikit-learn flask
```

4. Run the Python application:

```bash
python app.py
```

5. Open the local Flask URL displayed in the terminal.

## Project Objective
To develop a simple and understandable SMS classification system that helps identify potentially fraudulent and unwanted messages.

## Author
**Shaik Heera**

GitHub: https://github.com/shaikheera882-glitch
