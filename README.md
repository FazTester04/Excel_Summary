# 📊 Excel Summary Analyser

A simple yet powerful Python desktop tool that allows you to **drag and drop Excel files**, automatically read the **“SUMMARY” tab**, and display the overall **Pass / Fail / N/A / Not Tested** results — complete with a **visual chart and summary window**.

---

## 🚀 Features

- 🖱️ **Drag & Drop Excel Input** – Easily select or drop your Excel file.
- 📑 **Automatic Summary Detection** – Reads data from the “SUMMARY” worksheet.
- 📈 **Instant Visual Charts** – Displays a pie chart of Pass/Fail/N.A/Not Tested results.
- 🪟 **Pop-out Summary Window** – Shows test count and percentage summary.
- 🧪 **Mock Excel Generator** – Quickly generate a sample Excel file for testing.

---

## 🛠️ Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/<your-username>/excel-summary-analyser.git
   cd excel-summary-analyser
   ```

2. **Create a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate     # (Mac/Linux)
   venv\Scripts\activate        # (Windows)
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

   Or manually install:
   ```bash
   pip install pandas openpyxl matplotlib tk
   ```

---

## 📂 Project Structure

```
excel-summary-analyser/
│
├── excel_summary_analyser.py      # Main application script (UI + logic)
├── requirements.txt               # Python dependencies
├── README.md                      # Project documentation
└── sample_mock.xlsx               # Example generated test file
```

---

## ▶️ Usage

1. **Run the application**
   ```bash
   python excel_summary_analyser.py
   ```

2. **Choose or Drag & Drop** your Excel file onto the interface.

3. The app will:
   - Read the `SUMMARY` tab
   - Count `PASS`, `FAIL`, `N/A`, and `NOT TESTED`
   - Display a popup window with:
     - A data table
     - A pie chart of results

---

## 🧩 Mock Excel Generator

Click the **“Create Mock Excel”** button to generate a sample Excel file with random PASS/FAIL/N.A/NOT TESTED data — great for demo or testing.

---

## 📸 Screenshots

| Summary Window | Chart Example |
|----------------|----------------|
| *(coming soon)* | *(coming soon)* |

---

## 🧠 Requirements

- Python 3.9+
- pandas
- openpyxl
- matplotlib
- tkinter (comes preinstalled with Python)

---

## 💡 Future Improvements

- Support for multiple sheets
- Save result summary as PDF or CSV
- Theming (dark/light mode)
- Error handling improvements

---

## 👨‍💻 Author

**Fazni Alif Asyraf**  
TV Software Tester | Python Developer  
📍 Sony TV R&D (Malaysia)

---

## 🪪 License

This project is licensed under the **MIT License** – feel free to use and modify it.

---

## ⭐ Contribute

Pull requests and suggestions are welcome!  
If you like this project, please give it a ⭐ on GitHub — it helps a lot!
