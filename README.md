DemoQA Login Page Automation (Data-Driven PyTest Framework)


📘 Project Overview

This project automates the Login Page of DemoQA.com using:

Python + Selenium WebDriver

PyTest Framework

Page Object Model (POM)

Data-Driven Testing

HTML Reporting (pytest-html)


⚙️ Tools & Technologies Used

| Category        | Tool/Library            |

| Language        | Python                  |

| Automation Tool | Selenium WebDriver      |

| Test Framework  | PyTest                  |

| Design Pattern  | Page Object Model (POM) |

| Testing Type    | Data-Driven Testing     |

| Reporting       | pytest-html             |

| Browser         | Google Chrome           |



📂 Folder Structure


DemoQA_Login_Automation/

│

├── base_pages/

│   └── login_page.py          # Page Object file containing all login actions

│

├── test_case/

│   └── test_login.py          # PyTest file for executing login test cases

│

├── test_data/

│   └── login_data.py          # Test data (usernames, passwords, expected results)

│

├── conftest.py                # Browser setup and teardown using PyTest fixture

│

├── Report.html                # HTML report generated after test run

│

└── README.md                  # Project documentation



⚙️ How It Works

Browser Setup – conftest.py creates a browser instance using Chrome.

Page Object Model (POM) – login_page.py defines elements and functions (open page, enter data, click login).

Data-Driven Testing – login_data.py stores multiple username-password sets with expected results.

Test Execution – test_login.py runs all tests using PyTest parameterization.

Report Generation – pytest-html automatically generates a detailed Report.html.


🧾 About the HTML Report

The pytest-html report (Report.html) gives a complete summary after test execution:

Includes:

Total Tests Executed

Number of Passed and Failed Tests

Duration of Each Test

Environment Details (Python version, Platform, Browser, etc.)

Detailed Logs for Each Test

👩‍💻 Author

Usha Nazare

| Project Type           | Practice Project  |

Python Selenium Automation Tester


