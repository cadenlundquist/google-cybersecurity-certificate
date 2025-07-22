# Lab 06: Working with Strings for Security Tasks

- **Platform**: Google Cybersecurity Certificate  
- **Lab Focus**: String Manipulation and Slicing in Python for Security Automation

---

## 🧠 Overview

This lab focused on using Python’s string operations to manage and manipulate data frequently encountered in cybersecurity workflows. As a security analyst, string handling is essential for working with user and device identifiers, network addresses, and URLs.

The lab introduced string type conversion, conditional formatting of employee IDs, character extraction from device IDs, and parsing structured data from URLs. These techniques demonstrate how string manipulation supports data normalization, validation, and extraction in real-world security operations.

---

## ✅ Key Tasks Completed

- Converted a four-digit integer `employee_id` into a string using the `str()` function  
- Wrote a conditional statement to check if an employee ID met the new five-character length requirement  
- Used string concatenation to prepend a character (`"E"`) to a four-digit ID for standardization  
- Extracted individual characters from a device ID string using index notation  
- Created a string slice to retrieve the first three characters of a device ID  
- Parsed the protocol from a full URL by slicing the first eight characters (`"https://"`)  
- Located the starting index of a domain extension (`".com"`) using the `.index()` method  
- Stored the domain’s starting index in a variable and used slicing to extract `.com` from the URL  
- Used the `ind` variable to extract the website name portion of the URL dynamically

---

## 💻 Technical Skills Practiced

- Type conversion between integers and strings using `str()` and `type()`  
- String length validation using `len()`  
- Conditional statements for input validation  
- String concatenation for formatting data  
- String indexing and slicing for data extraction  
- URL parsing using `.index()` and dynamic slicing  
- Managing and manipulating string-based identifiers (e.g., employee and device IDs)

---

## 🔁 Reflections

This lab emphasized the importance of mastering string manipulation for data handling in cybersecurity contexts. Skills such as formatting employee IDs to meet policy standards, extracting meaningful components from device IDs, and parsing key parts of URLs are essential for automating data processing, validating input, and building incident response tools.

Python's built-in functions and methods like `len()`, `str()`, and `.index()` are powerful tools for efficiently handling and analyzing structured and semi-structured string data. As cybersecurity environments generate vast amounts of string-based logs and identifiers, these skills are foundational for analysts working in automation, monitoring, and scripting tasks.
