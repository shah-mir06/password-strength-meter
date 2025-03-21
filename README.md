# Password Strength Meter  

Welcome to **Password Strength Meter**, a simple yet effective tool built with Python and Streamlit to evaluate the strength of your passwords. This tool helps users determine whether their password is **weak, moderate, or strong**, encouraging better security practices.  

---

## Features  

- **Real-Time Password Strength Analysis** – Checks password strength instantly.  
- **Multiple Security Checks** – Evaluates password length, uppercase letters, digits, and special characters.  
- **User-Friendly Interface** – Simple input box and a one-click "Check Password" button.  
- **Helpful Feedback** – Provides suggestions based on password strength.  

---

## Installation & Usage  

### Clone the Repository  
```
git clone https://github.com/shah-mir06/password-strength-meter.git
cd password-strength-meter
```

### Install Dependencies  
Ensure **Python 3.x** is installed, then run:  
```
pip install -r requirements.txt
```

### Run the Application  
```
streamlit run password_meter.py
```

### How It Works  
1. **Enter a password** in the input box.  
2. **Click the "Check Password" button** to analyze its strength.  
3. **See the strength rating**:  
   - **Very Weak** – Lacks basic security requirements.  
   - **Weak** – Needs improvement, missing key elements.  
   - **Moderate** – Decent, but could be stronger.  
   - **Strong** – Secure and recommended.  

---

## Why Use This Tool?  

A weak password can lead to security vulnerabilities, making your accounts easy targets for hackers. This tool ensures that you are using **stronger passwords** by checking:  

**Minimum length requirement** (8+ characters)  
**At least one uppercase letter**  
**At least one number**  
**At least one special character (!@#$%^&*)**  

By following these guidelines, you can improve your cybersecurity and protect your personal data.  

---

## Contribute  

Want to enhance this tool? Fork the repository, make improvements, and submit a pull request. Contributions are welcome!  
