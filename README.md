# Automated LinkedIn Job Apply (Easy Apply only)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Selenium](https://img.shields.io/badge/Selenium-43B02A.svg?&style=flat&logo=selenium&logoColor=pink)](https://www.selenium.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5.svg?&style=flat&logo=linkedin&logoColor=blue)](https://www.linkedin.com/)
[![Python 3.8](https://img.shields.io/badge/Python-3.8-red.svg)](https://www.python.org/)

## Overview

This Python script automates the job application process on LinkedIn using Selenium. The script opens a specific job listing, signs in to the user's LinkedIn account, and applies to the job by filling out the necessary information.

## Prerequisites

Before using this script, ensure you have the following:

- Python installed on your machine.
- Selenium library: You can install it using `pip install selenium`.
- Webdriver for Chrome: Download the appropriate version from [ChromeDriver](https://sites.google.com/chromium.org/driver/) and specify its path in the script.
- Webdriver Manager (optional): If you want to automatically keep your ChromeDriver up to date, install it using `pip install webdriver-manager`.
- LinkedIn account credentials: Provide your LinkedIn login email, password, and phone number in the script.

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/akumarm23/Day59-AutoLinkedIn.git
   ```

2. Open the script (`main.py`) in a text editor.

3. Update the following variables with your information:

   - `ACCOUNT_EMAIL`: Your LinkedIn login email.
   - `ACCOUNT_PASSWORD`: Your LinkedIn login password.
   - `PHONE`: Your phone number.
   - `chrome_driver_path`: Path to your ChromeDriver executable.
   - (Optional) `ChromeDriverManager`: If using, specify the path to your ChromeDriver folder.

## Usage

1. Run the script:

   ```bash
   python main.py
   ```

2. The script will open the specified LinkedIn job listing and automate the application process.

3. Manually solve the CAPTCHA when prompted.

4. The script will apply to each job listing and print messages indicating the progress.

## Notes

- The script is designed for a specific LinkedIn job listing. Modify the URL in the script to target a different job listing.
- Ensure that your LinkedIn account is in good standing to avoid issues with the automated application process.
- Keep the Chrome browser open during script execution, and do not interact with the browser while the script is running.

## Disclaimer

Use this script responsibly and in compliance with LinkedIn's terms of service. The automated application process may be subject to changes on the LinkedIn platform, and the script may require updates accordingly.

--
