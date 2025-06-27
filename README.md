# Login Automation Dashboard (Jupyter Edition)

This project is a desktop-style login automation tool built in a **Jupyter Notebook** using `customtkinter` for the GUI and `selenium` for browser automation. It automates logging into the [emaktab.uz](https://login.emaktab.uz/) platform using user credentials stored in an Excel file.

---

## Features

- CustomTkinter-based modern interface inside a Python notebook
- Dark and light theme switcher
- Select `.xlsx` file with login credentials
- Automated login and logout using Selenium WebDriver
- Progress bar and real-time logging
- Multithreaded operation to keep UI responsive

---

## Technologies Used

- Python 3.10+
- Jupyter Notebook
- CustomTkinter
- Selenium
- Pandas
- ChromeDriver

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/login-automation-dashboard.git
cd login-automation-dashboard
````

### 2. Create a Virtual Environment (Recommended)

```bash
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install Required Libraries

```bash
pip install customtkinter selenium pandas openpyxl notebook
```

### 4. Start the Jupyter Notebook

```bash
jupyter notebook
```

Then open the notebook file (e.g., `login_dashboard.ipynb`).

---

## Excel File Format

Your Excel file must be in `.xlsx` format with the following column headers:

| Login          | Password    |
| -------------- | ----------- |
| user\@example1 | password123 |
| user\@example2 | password456 |

* Column names must be exactly: `Login` and `Password`
* All credentials will be used sequentially by the automation script

---

## Configure ChromeDriver

Update the following line in the notebook code:

```python
CHROME_DRIVER_PATH = "/absolute/path/to/chromedriver"
```

Make sure your ChromeDriver version matches your installed Chrome browser.

---

## Running the App

After opening the notebook:

1. Run all cells (Cell → Run All)
2. A GUI window will open
3. Select the Excel file
4. Click "Boshlash" to start automation

---

## Notes

* Do not run inside online notebook platforms (e.g., Google Colab) — it requires desktop GUI and local ChromeDriver.
* This tool is for educational and administrative use only.
* Make sure you have permission to access the accounts being automated.
