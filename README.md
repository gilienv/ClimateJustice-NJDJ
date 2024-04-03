# National Judicial Data Grid (NJDG) Scrapper

## Description

This Python script is designed to extract case details from the National Judicial Data Grid (NJDG) web app using Selenium WebDriver and save them to a CSV file in the output folder within the current date folder. The script navigates through the website with respect to state names, clicks on total cases, then proceeds and solves 2 CAPTCHAs internally. After solving them, it extracts case details and saves them to a CSV file. This logic runs in a loop until data from the specified states is extracted.

For more information about NJDG, please visit [National Judicial Data Grid](https://njdg.ecourts.gov.in/).


## Table of Contents

- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Dependencies

- **Selenium**: A Python library for automating web browsers.
- **PIL (Python Imaging Library)**: Required for image manipulation.
- **OpenCV**: A library for computer vision and image processing tasks. Used to enhance the captcha image for text extraction.
- **Firefox WebDriver**: WebDriver for the Firefox browser. Automatically managed by `webdriver_manager`.
- **Pytesseract**: Python binding to the Tesseract OCR engine for extracting text from images.


## Usage

Instructions and examples for usage of your project.

## Contributing

Guidelines for contributing to the project.

## Contact

If you encounter any difficulties during the process of downloading dependencies or executing the Python scripts, feel free to reach out for assistance. You can contact me via email at itsabdullah.cg@gmail.com or message me on WhatsApp at +91 9540743471. I'm here to help you resolve any issues and ensure a smooth experience with the setup and usage of the provided scripts.
