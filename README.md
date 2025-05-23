# 🏦 Bank Account Management System with Twilio SMS Notifications

This Python application simulates a bank account system, enabling users to perform deposit and withdrawal operations. It integrates Twilio's API to send SMS notifications for each transaction and employs Python's logging module to maintain a record of all activities.

## 🚀 Features

- **Deposit & Withdrawal Operations**: Handle basic banking transactions with input validation.
- **SMS Notifications**: Send real-time SMS alerts for each transaction using Twilio.
- **Logging**: Record all transactions and errors in a log file for auditing purposes.
- **Custom Exceptions**: Gracefully handle invalid operations with descriptive error messages.

## 🧰 Prerequisites

- **Python 3.6 or higher**
- **Twilio Account**: Sign up at [Twilio](https://www.twilio.com/) and obtain:
  - **Account SID**
  - **Auth Token**
  - **Twilio Phone Number** (with SMS capabilities)
- **Python Packages**:
  - `twilio`
  - `logging` (standard library)

