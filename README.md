# 💉 SQL Injection on DVWA (Low Security)

## 📌 Objective

To demonstrate SQL Injection vulnerability on DVWA.

## 🛠 Tools Used

* Kali Linux
* DVWA (Damn Vulnerable Web Application)

## ⚙️ Setup

* DVWA installed on local server
* Apache and MySQL services started
* Security level set to LOW

## 🧪 Steps Performed

1. Opened DVWA in browser
2. Logged in using default credentials
3. Set security level to LOW
4. Navigated to SQL Injection page
5. Entered payload in input field

## 💥 Payload Used

1' OR '1'='1

## 🔍 Explanation

The payload modifies the SQL query so that the condition always evaluates to TRUE. This bypasses input validation and forces the database to return all records.

## 📊 Result

* Successfully retrieved multiple user records
* Demonstrated SQL Injection vulnerability

## ⚠️ Vulnerability

The application does not validate user input, making it vulnerable to SQL Injection attacks.

## 🛡️ Prevention

* Use prepared statements
* Input validation
* Parameterized queries

## ✅ Conclusion

SQL Injection was successfully performed, showing how insecure input handling can expose sensitive data.

## ⚠️ Disclaimer

This experiment was performed in a controlled lab environment for educational purposes only.
