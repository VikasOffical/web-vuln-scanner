# **Web Application Vulnerability Scanner**

# **Overview**

This tool scans web applications for common vulnerabilities such as SQL Injection (SQLi) and Cross-Site Scripting (XSS) by analyzing forms and injecting test payloads.

# **Features**

Extracts forms from a given web page.

Tests forms for SQL Injection vulnerabilities.

Tests forms for Cross-Site Scripting (XSS) vulnerabilities.

Reports potential security weaknesses in web applications.

# **Installation**

## **Prerequisites**

Ensure you have Python 3 installed. Then, install the required dependencies:

pip install requests beautifulsoup4

# **Usage**

## **Run the script:**

python scanner.py

Enter the target URL when prompted.

Check the output for potential vulnerabilities.

# **Example**

Enter the URL to scan: http://example.com
[+] Scanning http://example.com...
[*] Found 2 forms on http://example.com
[!] Possible SQL Injection vulnerability detected at http://example.com/login
[+] Scan completed.

# **Disclaimer**

🚨 Only use this tool on websites you own or have explicit permission to test. Unauthorized testing is illegal!

# **License**

This project is open-source and provided under the MIT License.

Happy Ethical Hacking! 🔒🚀

