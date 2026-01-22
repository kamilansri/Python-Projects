# 🐍 Python Mini-Projects: Learning by Doing

This repository documents my journey learning Python through practical, real-world applications. It contains a collection of scripts and mini-projects focused on automation and logic building.

---

## 📂 Projects Overview

### 1. Currency Converter 💱
A command-line tool that converts amounts between different currencies based on exchange rates.



**Key Features:**
* Accepts user input for source currency, target currency, and amount.
* Performs real-time (or static) calculations.
* Formats output to 2 decimal places.

**Concepts Applied:**
* **Data Types:** Floats and Strings.
* **Dictionaries:** Storing exchange rates (e.g., `{'USD': 1.0, 'EUR': 0.85}`).
* **Math Operations:** performing the conversion logic.
* **APIs (Optional):** Fetching live rates using libraries like `requests`.

### 2. Random Password Generator 🔐
A security tool that generates strong, random passwords to specific user requirements.



**Key Features:**
* User defines the length of the password.
* Option to include uppercase, numbers, and special symbols.
* Ensures randomness for high security.

**Concepts Applied:**
* **The `random` Module:** Using `random.choice()` and `random.shuffle()`.
* **The `string` Module:** Accessing `ascii_letters`, `digits`, and `punctuation`.
* **Loops:** Iterating to build the password string.
* **Input Validation:** Ensuring the user requests a valid length.

---

## 💻 Code Snippets

### Currency Conversion Logic
```python
def convert_currency(amount, rate):
    """
    Converts amount based on the provided exchange rate.
    """
    return round(amount * rate, 2)
```
---
## 📚 Future Improvements
* **GUI:** Adding a graphical interface using `Tkinter` or `PyQt`.
* **Live Data:** Connecting the Currency Converter to a live API (like Open Exchange Rates).
* **Clipboard Support:** Automatically copying the generated password to the clipboard using `pyperclip`.

---

## 🔗 Resources
* **[Python Random Module Docs](https://docs.python.org/3/library/random.html)**
* **[Python String Methods](https://docs.python.org/3/library/string.html)**
