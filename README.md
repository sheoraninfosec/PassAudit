# 🔐 PassAudit: Password Generator & Strength Checker

**PassAudit** is a lightweight, client-side web application that lets you securely generate strong passwords and evaluate their strength using a transparent, rule-based scoring system. Ideal for developers, security-conscious users, or anyone who wants a no-nonsense tool to assess password quality — fast, offline, and private.

---

## 🚀 Features

- ✅ **Password Generation**
  - Custom length (6–24 characters)
  - Toggle uppercase, lowercase, numbers, and symbols
- ✅ **Rule-Based Strength Evaluation**
  - Score based on length, complexity, repetition, and common patterns
- ✅ **Color-Coded Strength Bar**
  - Labels: Very Weak → Very Strong
- ✅ **Fully Offline**
  - Works in your browser — no servers, no tracking
- ✅ **All-in-One HTML File**
  - No dependencies or installation required

---

## 🖥️ Live Demo

> Coming soon... *(You can deploy using GitHub Pages or Netlify)*

---

## 📸 Screenshot

![PassAudit UI](screenshot.png)  
*Simple interface to generate and audit passwords instantly.*

---

## ⚙️ How to Use

1. Clone or download this repo.
2. Open `passaudit.html` in your web browser.
3. Adjust character types and password length.
4. Click **Generate Password**.
5. See the strength score and feedback instantly.

---

## 🧠 How Password Strength is Scored

| Criteria                                  | Points   |
|-------------------------------------------|----------|
| Length ≥ 8                                | +10      |
| Length ≥ 12                               | +10      |
| Contains Uppercase                        | +10      |
| Contains Lowercase                        | +10      |
| Contains Numbers                          | +10      |
| Contains Symbols                          | +15      |
| Repeated characters (3+)                  | −10      |
| Common patterns (e.g. `abc`, `123`, etc.) | −20      |
| Consecutive same-type characters          | −5       |

### Score Breakdown

| Score Range | Rating       |
|-------------|--------------|
| 0–29        | 🔴 Very Weak |
| 30–49       | 🟠 Weak      |
| 50–69       | 🟡 Good      |
| 70–89       | 🟢 Strong    |
| 90–100      | 💙 Very Strong |

---

