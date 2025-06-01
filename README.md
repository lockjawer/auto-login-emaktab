# Login Automation Dashboard

**Login Automation Dashboard** is a modern desktop application built with `customtkinter` and Python. It enables users to automate the login process for a list of credentials stored in an Excel file.

---

## Features

- **Modern UI:** Dark and light themes with a sleek, responsive interface.
- **File Upload:** Easily upload Excel files containing login credentials.
- **Progress Tracking:** Real-time progress updates with a progress bar.
- **Activity Logs:** Logs all activity for better transparency and debugging.
- **Start/Stop/Reset Controls:** Manage automation with intuitive controls.
- **Multi-threaded Execution:** Keeps the UI responsive during long tasks.

---


## Prerequisites

To run this application, you need the following:

1. Python 3.8 or later
2. The required Python libraries (see below)
3. Google Chrome installed
4. ChromeDriver installed ([Download ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads))

---

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/login-automation-dashboard.git
    cd login-automation-dashboard
    ```

2. Install the required Python libraries:

    ```bash
    pip install -r requirements.txt
    ```

3. Ensure the `CHROME_DRIVER_PATH` is correctly set in the script to match your system.

---

## Usage

1. Run the application:

    ```bash
    python main.ipynb
    ```

2. Upload an Excel file containing the login credentials. Ensure the file has the following columns:
    - `Login`
    - `Password`

3. Click "Start" to begin the automation process. The progress bar and activity logs will display real-time updates.

4. You can stop or reset the automation at any time using the corresponding buttons.

---

## File Format

The Excel file should look like this:

| Login           | Password      |
|-----------------|---------------|
| user1@example.com | password123  |
| user2@example.com | mypassword456 |

---

## Technologies Used

- **Python**
- **CustomTkinter**: For the modern user interface
- **Selenium**: For web automation
- **Pandas**: For reading Excel files

---

## Roadmap

- Add support for additional websites.
- Enhance error handling and logging.
- Include features for scheduling automation tasks.

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Add feature-name"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

