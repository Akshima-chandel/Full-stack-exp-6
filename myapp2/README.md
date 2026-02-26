# Experiment – 2  
## Client-Side Form Validation (React + Vite)

### 📌 Aim
To validate form inputs on the client side before submission using React.

---

## 📖 Theory

Client-side validation ensures correctness of user input before sending data to the server.  
It provides immediate feedback, improves user experience, and reduces unnecessary server requests.

In this experiment, form validation is implemented using:
- React useState hook
- Regular Expressions (Regex)
- Conditional rendering for error messages

---

## 🛠 Technologies Used

- React (Vite)
- JavaScript (ES6)
- CSS3
- Regular Expressions (Regex)

---

## 📂 Project Structure

myapp2/
│
├── src/
│ ├── App.jsx
│ ├── App.css
│ └── main.jsx
│
├── index.html
├── package.json
└── README.md


---

## 🧾 Form Fields

This form contains only two fields:

1. Email ID  
2. Password  

---

## ✅ Email Validation Rules

- Must contain exactly one `@`
- Must contain a valid domain
- Must end with:
  - `.com`
  - `.in`
  - `.org`
  - `.net`
  - `.edu`
  - `.gov`
  - `.co`
  - `.io`
- No invalid structure allowed
- No empty input

### ✔ Valid Examples

arnav@gmail.com
user123@company.in
abc@domain.org


### ❌ Invalid Examples

arnav@gmail
arnav@.com
@domain.com
arnav@@gmail.com


---

## 🔐 Password Validation Rules

Password must:

1. Start with a Capital Letter
2. Contain at least one number
3. Contain at least one special character (!@#$%^&*)
4. Be at least 5 characters long

### ✔ Valid Examples

A1@bc
Z9#xy
P5$abcd


### ❌ Invalid Examples

a1@bc (Does not start with capital)
Aabcd (No number or special character)
A1abc (No special character)


---

## ⚙️ How to Run the Project

1. Open terminal
2. Navigate to project folder:

cd exp6/myapp2


3. Install dependencies:

npm install


4. Start development server:

npm run dev


5. Open browser at:

http://localhost:5173


---

## 🎯 Output Behavior

- If input is invalid → Error message displayed below the field
- If input is valid → Alert box displays:
  - Email
  - Password
- Form resets after successful submission

---

## 🧠 Regex Used

![succesful]<img width="632" height="358" alt="Screenshot 2026-02-26 103837" src="https://github.com/user-attachments/assets/659feb30-bb1e-4033-be09-f772cb64af03" />

![email error]<img width="1146" height="830" alt="Screenshot 2026-02-26 103720" src="https://github.com/user-attachments/assets/9d1662cb-7f9a-41bd-bd06-2361f35e402d" />

![password error]<img width="743" height="680" alt="Screenshot 2026-02-26 104915" src="https://github.com/user-attachments/assets/e7098fa1-2777-4ed8-b772-3b4807ffaaf2" />




