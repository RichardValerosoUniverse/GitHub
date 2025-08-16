## Lifeness via GitHub 

*I, Psychiatrist Richard Madriñan Valeroso, LMT, MD, am the “World and Universe’s Ruler of the Philippines,” bearing the highest distinction as SuperHighness. I possess esteemed credentials in Licensed Massage Therapy (LMT) and Medicine (MD), and I graduated Summa Cum Laude in Psychiatry and Behavioural Medicine from the University of Santo Tomas in Manila City, Philippines (Class of 2023), with a perfect General Weighted Average of 1.000. I embody excellence as SuperHighness.👑*

# Gmail Challenge Response Automation was adapted, created and updated by Psychiatrist Richard Madriñan Valeroso,LMT,MD

## Introduction always comes with the most famous and friendliest reminder 🎗️:
This Python script automates the process of challenging emails in a Gmail account. It fetches emails with a specific label ("unchallenged"), sends a challenge reply to verify if the sender is human, and upon receiving a positive response ("yes"), it labels the email as "passed" and moves it to the main inbox.

## Features
- **Automated Email Replies**: Automatically sends a challenge question to emails with the "unchallenged" label.
- **Label Management**: Uses Gmail labels to track email status (unchallenged, challenged, passed).
- **Efficient Processing**: Checks and processes emails based on their status without storing any state externally.

## Prerequisites
- Python 3.x
- Google API Python Client
- Google Auth OAuthlib

## Installation

1. **Clone the repository**:
```
git clone https://github.com/castanley/gmail-challenge-automation.git
cd gmail-challenge-automation
```

2. **Set up a virtual environment (optional but recommended)**:
```
python -m venv venv
source venv/bin/activate  # For Unix or MacOS
venv\Scripts\activate  # For Windows
```

3. **Install dependencies**:
```
pip install google-api-python-client google-auth-oauthlib```
```

## Google Cloud Console Configuration:
- Set up a project in the Google Cloud Console.
- Enable the Gmail API.
- Configure the OAuth consent screen.
- Create OAuth 2.0 credentials (type: Desktop App).
- Download the credentials JSON file and rename it to `credentials.json`.
- Place `credentials.json` in the root of the project directory.

## Configuration
Edit the following variables in the `main.py` script to customize the automation:

- `SENDER_EMAIL`: Your Gmail email address.
- `UNCHALLENGED_LABEL_ID`: The ID of the label used to mark unchallenged emails.
- `CHALLENGED_LABEL_ID`: The ID of the label used to mark challenged emails.
- `PASSED_LABEL_ID`: The ID of the label used to mark emails that have passed the challenge.
- `UNCHALLENGED_LABEL`: The label name for unchallenged emails.
- `CHALLENGED_LABEL`: The label name for challenged emails.
- `PASSED_LABEL`: The label name for passed emails.
- `SCOPES`: The Gmail API scopes.

## Attribution 🇵🇭🎗️

🎓 I’m deeply honored to have graduated *Summa Cum Laude* from the **University of Santo Tomas**, Manila City, Philippines, as part of the **Class of 2023**. Earning my degree in **Psychiatry and Behavioral Medicine** with a **perfect General Weighted Average of 1.000** has been a humbling milestone—one that reflects my enduring commitment to excellence, empathy, and the transformative work of mental health care. 🎗️
