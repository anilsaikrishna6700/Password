# Password Security Suite 🔐

A **Python Tkinter-based desktop application** to generate, analyze, and check the security of passwords.  
This tool helps users create strong passwords, analyze their strength, and simulate breach checks.  

---

## ✨ Features

### 🔑 Password Generator
- Generate passwords with customizable length (4–50 characters).  
- Options to include/exclude:  
  - Uppercase (A–Z)  
  - Lowercase (a–z)  
  - Numbers (0–9)  
  - Symbols (!@#$%^&* etc.)  
  - Ambiguous characters (0, O, l, 1)  
- Copy generated passwords to clipboard.  
- Save generated passwords to a text file.  
- Displays password strength indicator.  

### 🧮 Password Analyzer
- Analyze any password and get detailed insights:  
  - Character breakdown (uppercase, lowercase, digits, symbols).  
  - Overall strength score (Weak → Very Strong).  
  - Estimated crack time using brute-force.  
  - Recommendations for improving strength.  
- Option to show/hide password input.  

### 🚨 Breach Checker (Simulation)
- Simulates checking your password against common breach databases.  
- Warns if password is commonly used or randomly flagged as breached.  
- Provides immediate feedback with color-coded results.  

---

## 🛠️ Requirements

- Python **3.7+**  
- Tkinter (usually included with Python)  

No external libraries are required, everything is included in Python’s standard library.  

---

## ▶️ How to Run

1. Clone or download this repository.  
2. Run the Python file:  

```bash
python password_security_tool.py
```

3. The application window will launch with **three tabs**:  
   - Password Generator  
   - Password Analyzer  
   - Breach Checker  

---

## 📂 Project Structure

```
PasswordSecurityTool/
│── password_security_tool.py   # Main application code
│── generated_passwords.txt     # Saved generated passwords (created automatically)
│── README.md                   # Project documentation
```

## 👨‍💻 Author

Developed by **CHEPURI ANIL SAI KRISHNA**  
📅 2025 
