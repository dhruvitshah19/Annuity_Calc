
# 📈 Annuity Calculator Web App

This project is a simple and intuitive web-based **Annuity Calculator** that helps users estimate the future value of an investment or savings account with recurring payments. The application is built using **Flask (Python)** for the backend and **HTML/CSS** for the frontend.

### 🚀 Features

- Web interface to input annuity parameters:
  - Starting capital
  - Annual interest rate
  - Periodic payment
  - Time period (in years)
- Computes the **future value** of an ordinary annuity using the standard formula.
- Hosted and deployed globally using **Render** for public access.

---

### 🧮 Formula Used

\[
\text{Future Value} = P \left( \frac{(1 + r)^t - 1}{r} \right) + C \cdot (1 + r)^t
\]

Where:
- `P` = periodic payment
- `r` = interest rate (as a decimal)
- `t` = time period (in years)
- `C` = initial capital

---

### 🛠️ Technologies Used

- Python (Flask)
- HTML5 & CSS3
- Jinja2 templating (for dynamic result display)
- Hosted on Render

---

### 📁 Project Structure

```
Annuity_Calculator/
├── Annuity_Calc.py               # Flask app with calculator logic
├── templates/
│   └── Annuity_Calc.html         # Web form and display page
├── requirements.txt              # Dependencies for deployment
└── README.md                     # Project overview and usage
```

---

### 💡 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Annuity_Calculator.git
   cd Annuity_Calculator
   ```

2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:
   ```bash
   python Annuity_Calc.py
   ```

4. Visit `http://localhost:5000` in your browser.

---

### 🌐 Deployment

Deployed using [Render](https://render.com/). Visit the live calculator [here](https://annuity-calc-1.onrender.com/).

---

### 📄 License

MIT License
