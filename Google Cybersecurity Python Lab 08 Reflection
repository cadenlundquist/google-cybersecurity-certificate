# Lab 08: Extracting Device IDs and IP Addresses Using Regular Expressions

- **Platform**: Google Cybersecurity Certificate  
- **Lab Focus**: Pattern Matching with Python Regular Expressions for Security Log Analysis

---

## 🧠 Overview

In this lab, the focus was on using Python’s `re` module to extract and analyze security-related data from system logs. As a security analyst, identifying devices that require software updates and detecting suspicious login activity based on IP addresses is a critical part of threat detection and mitigation. This lab simulated real-world tasks where automation using regular expressions can greatly enhance the speed and accuracy of log analysis.

---

## ✅ Key Tasks Completed

- Imported the `re` module to use regular expression functions  
- Extracted device IDs that start with `r15` from a string of mixed IDs to identify systems needing OS updates  
- Created a regex pattern (`r15\w+`) to match alphanumeric device IDs beginning with `r15`  
- Used `re.findall()` to extract all device IDs matching the target pattern  
- Displayed a multi-line string (`log_file`) simulating login activity with usernames, timestamps, and IP addresses  
- Built and tested multiple regex patterns to match IP addresses in the format `xxx.xxx.xxx.xxx`:
  - Strict: `\d\d\d\.\d\d\d\.\d\d\d\.\d\d\d`  
  - Flexible: `\d+\.\d+\.\d+\.\d+`  
  - Balanced: `\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3}`  
- Filtered out invalid IP addresses by constraining each segment to 1–3 digits  
- Compared valid IPs against a list of flagged addresses to identify ones needing investigation  
- Used a `for` loop with conditionals to display custom messages for flagged vs. unflagged IPs

---

## 💻 Technical Skills Practiced

- Importing and using the `re` module for regular expressions  
- Writing and refining regex patterns to extract specific formats from unstructured data  
- Using `re.findall()` to retrieve all matches from a string  
- Validating data format (like IP addresses) using quantifiers and constraints  
- Creating conditionals to compare data values against known threats  
- Automating log analysis with iteration and logic-based filtering

---

## 🔁 Reflections

This lab emphasized how powerful and versatile regular expressions can be in cybersecurity tasks such as log analysis, device inventory review, and anomaly detection. It was insightful to see how small changes in regex syntax drastically affected pattern matching outcomes.

Understanding how to filter out invalid data—such as identifying outdated systems via device IDs or matching flagged IPs—is crucial for scalable and accurate incident response. This hands-on experience demonstrated how combining regex with Python logic allows analysts to sift through complex logs efficiently and systematically prioritize threats for further analysis.
