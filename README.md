# 🔐 PassShield

A simple and user-friendly web application that analyzes the strength of a password based on various security criteria and suggests improvements for weak passwords.

## 📌 Project Overview

This project evaluates user-entered passwords and checks whether they meet common security requirements such as:

* Minimum password length
* Uppercase letters
* Lowercase letters
* Numeric digits
* Special characters

The application then classifies the password as **Weak**, **Moderately Strong**, or **Strong**, and suggests a stronger password when necessary.

---

## ✨ Features

### Password Analysis

* Checks password length
* Detects uppercase letters
* Detects lowercase letters
* Detects digits
* Detects special characters

### Strength Classification

* 🔴 Weak
* 🟠 Moderately Strong
* 🟢 Strong

### Requirement Validation

Displays missing security requirements such as:

* Minimum 8 characters
* Uppercase letter
* Lowercase letter
* Digit
* Special character

### Password Suggestions

Automatically generates a stronger password suggestion by adding missing components and ensuring the minimum length requirement is met.

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)

No external libraries or frameworks were used.

---

## 📂 Project Structure

```text
Password-Strength-Analyzer/
│
├── index.html
├── README.md
```

---

## Live Demo

> https://GUHAN-R2987.github.io/PassShield/

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/password-strength-analyzer.git
```

2. Open the project folder.

3. Open `index.html` in any modern web browser.

No installation or setup is required.

---

## 📊 Password Evaluation Criteria

| Requirement          | Points |
| -------------------- | ------ |
| Minimum 8 Characters | 1      |
| Uppercase Letter     | 1      |
| Lowercase Letter     | 1      |
| Digit                | 1      |
| Special Character    | 1      |

### Strength Rules

* **Weak** → Password length less than 8 characters
* **Moderately Strong** → Length ≥ 8 but missing one or more requirements
* **Strong** → Meets all requirements

---

## 📸 Sample Output

### Weak Password

Input:

```text
hello
```

Output:

```text
❌ Minimum 8 Characters
❌ Uppercase Letter
❌ Digit
❌ Special Character

Strength: Weak

Suggested Password:
helloA1@X
```

---

### Strong Password

Input:

```text
Hello123@
```

Output:

```text
Strength: Strong
```

---

## 🎯 Learning Outcomes

Through this project, I learned:

* HTML page structure
* CSS styling and layout
* JavaScript DOM manipulation
* Form handling
* Regular Expressions (Regex)
* Password security concepts
* User interface design fundamentals

---

## 🔮 Future Improvements

* Show/Hide Password feature
* Password strength meter bar
* Copy suggested password button
* Password history tracking
* Password reuse prevention using Local Storage or Database
* Dark/Light theme support

---

## 👨‍💻 Author

Developed as part of an Internship Task to learn password security concepts and web development fundamentals.

