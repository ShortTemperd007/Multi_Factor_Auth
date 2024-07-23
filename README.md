# Multi_Factor_Auth
A python based  application for Applying Multifactor authentication


Two-Factor Authentication System
This Python application provides a two-factor authentication (2FA) system with registration, login, and password reset functionalities using Tkinter for the GUI. Key features include:

User Registration: Collects user information (name, email, password) and generates a QR code for 2FA setup.
Login: Validates user credentials and sends a one-time password (OTP) to the user's email for secure login.
Password Reset: Allows users to reset their password after verification.
Enhanced Security: Utilizes encryption for storing passwords and OTPs.
Technologies Used
Tkinter: For creating the GUI.
pyotp: For generating OTPs and QR codes.
qrcode: For creating QR codes.
PIL: For handling image processing.
cryptography: For password encryption and decryption.
smtplib: For sending OTPs via email.
Installation
Ensure you have Python installed.
Install the required packages:
bash
Copy code
pip install pyotp qrcode pillow cryptography
Usage
Run the script using Python. Follow the on-screen instructions to register, log in, or reset your password.
