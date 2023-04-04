## Introduction
This is a tool that helps automatically open web pages using Python code. It is used to open and access web pages from pre-written Python source files.

## Installation
Install the required libraries by using the following command on the terminal:
`pip install selenium`

## Copy code
pip install selenium
Then, download and install the Chrome web browser (or other browser if you want to use).

## Usage
1. Create a new Python file and import the necessary libraries.
`from selenium import webdriver`

2. Create a browser object using the previously installed Edge browser.
`browser = webdriver.Chrome('/path/to/msedgedriver')`

3. Use the get() method to access the web page.
`browser.get('http://example.com')`

4. When finished, close the browser using the close() method.
`browser.close()`

5. Run the Python code to open your web page.

# Note
- You need to use a browser installed on your system to use this tool.
- Make sure you have installed the appropriate version of Selenium for your browser version.
