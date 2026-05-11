#  Password Strength Analyzer
A modern and interactive Password Strength Analyzer built using HTML, CSS, and JavaScript.  
This web application evaluates password strength in real-time and provides feedback and strong password suggestions to help users create secure passwords.

---

#  Features

##  Real-Time Password Analysis
The application checks password strength instantly while the user types.

##  Dynamic Strength Meter
A visual strength bar updates automatically based on the password score.

## Password Strength Levels
The analyzer categorizes passwords into:
- Weak
- Medium
- Strong

##  Detailed Weakness Detection
The system identifies:
- Short passwords
- Missing uppercase letters
- Missing lowercase letters
- Missing numbers
- Missing special characters
- Repeated characters
- Common weak passwords

##  Strong Password Suggestions
If the password strength is weak, the application automatically generates a stronger password suggestion.

##  Modern Responsive UI
The project includes a clean dark-themed user interface with smooth styling and organized result sections.

---

#  Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)

---

#  Password Strength Criteria

The password score starts from **100** and deductions are applied based on weaknesses.

---

## 🔹 Length Rules

| Password Length | Result |
|----------------|--------|
| 5 characters or less | Very Weak (-40 points) |
| 6–10 characters | Medium (-15 points) |
| 11+ characters | Strong (No deduction) |

---

##  Character Variety Checks

| Requirement | Deduction |
|-------------|-----------|
| No uppercase letters | -20 |
| Less than 2 uppercase letters | -5 |
| No lowercase letters | -20 |
| Less than 2 lowercase letters | -5 |
| No numbers | -20 |
| Less than 2 numbers | -5 |
| No special characters | -20 |
| Less than 2 special characters | -5 |

---

##  Common Weakness Detection

### Repeated Characters
Passwords containing repeated patterns such as:
```text
aaaa
1111
2006
