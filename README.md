# SQLite CSV Importer with Logging

This Python project allows you to import a CSV file into an SQLite database, log the process, and view the imported data using `pandas`.

---

## 📁 Project Structure

your-project/
├── extracted_data.csv # Input CSV file
├── sqlite_loader.py # Main script
├── test_class.db # SQLite database (auto-created)
├── test.log # Log file (auto-generated)
├── requirements.txt # Python dependencies
└── README.md # Documentation


---

## 🚀 Features

- ✅ Connects to SQLite database (creates file if not exists)
- 📄 Reads structured CSV input using `pandas`
- 🧱 Dynamically creates table based on CSV columns
- 📥 Inserts all CSV records into the table
- 📤 Reads table data back into a DataFrame
- 🧾 Logs all actions to both file and console
- 🔁 Optional table deletion for clean test runs

---

## 📦 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
