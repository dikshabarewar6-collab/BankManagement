# Glow Bank – Bank Management System

An interactive banking web app built with Python and Streamlit. It was rebuilt from a console-based Bank class into a web interface, with account data stored in a local JSON file.

## Features
- Create an account with input validation (age 18+, valid email, 10-digit phone, 4-digit PIN with confirmation)
- Auto-generated unique account number
- Login with account number and PIN
- Deposit and withdraw money (insufficient balance check)
- View account details and balance
- Update name, email, phone number and PIN
- Close account with confirmation
- Home dashboard showing total accounts, total balance and average balance
- Data saved locally in `database.json`

## Tech Stack
Python, Streamlit, JSON

## Concepts Used
Functions, conditional statements, loops, file handling (JSON), input validation and session state management.

## Project Structure
```
BankManagement/
├── app.py             # Streamlit web app (Glow Bank)
├── main.py            # Original console-based Bank class
├── database.json      # Account data storage
├── requirements.txt   # Dependencies
└── README.md
```

## Run Locally
```bash
git clone https://github.com/dikshabarewar6-collab/BankManagement.git
cd BankManagement
pip install -r requirements.txt
streamlit run app.py
```

## Limitations
- Demo project: PINs are stored as plain numbers in the JSON file, so it is not suitable for real banking use
- No transaction history

## Future Improvements
- Hash PINs and add stronger authentication
- Add transaction history
- Move storage from JSON to a database such as PostgreSQL

## Author
**Diksha Barewar**
B.Tech AI & ML, Technocrats Institute of Technology & Science, Bhopal
[GitHub](https://github.com/dikshabarewar6-collab)
