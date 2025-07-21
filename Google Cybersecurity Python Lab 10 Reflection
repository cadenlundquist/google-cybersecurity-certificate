# Lab 10: Removing Unauthorized IPs from an Access List

- **Platform**: Google Cybersecurity Certificate  
- **Lab Focus**: Reading, Filtering, and Rewriting Access Control Files Using Python

---

## 🧠 Overview

In this lab, I worked with a text file containing IP addresses permitted to access restricted systems. As a security analyst, keeping access control lists up-to-date is critical to ensure only authorized users can reach secure resources. The lab simulated a real-world scenario in which unauthorized IP addresses needed to be removed from the access list. I used Python’s built-in file-handling and list manipulation features—including `with open()`, `.read()`, `.split()`, `.remove()`, and `.write()`—to automate the cleanup process. By the end of the lab, I created a reusable function to update the list more efficiently.

---

## ✅ Key Tasks Completed

- Assigned a filename to a variable (`import_file`) and defined a list of unauthorized IPs (`remove_list`)  
- Read the contents of `allow_list.txt` using `with open(..., "r")` and `.read()`  
- Split the space-separated string into a Python list of IP addresses  
- Iterated through the list and removed any matching IPs found in `remove_list`  
- Used `" ".join()` to convert the cleaned list back into a single string  
- Rewrote the file using `with open(..., "w")` and `.write()` to update the access list  
- Verified the update by reopening and printing the file contents  
- Wrapped the entire process in a reusable function `update_file()`  
- Called the function with a second set of unauthorized IPs to simulate another update

---

## 💻 Technical Skills Practiced

- Reading and writing text files in Python  
- Using `with open()` context managers for safe file access  
- String splitting and joining for data manipulation  
- List iteration and conditional removal of values  
- Function definition and reuse for automation  
- Verifying access control list updates through file inspection

---

## 🔁 Reflections

This lab reinforced how Python can be used to manage real-world security tasks such as access list maintenance. Automating the removal of unauthorized IPs not only improves consistency and accuracy but also significantly reduces the risk of human error. Defining the `update_file()` function made the process repeatable and easy to adapt for future changes.

One technical challenge was handling list mutations during iteration, which required careful logic to avoid skipping or missing entries. Understanding how to safely edit and overwrite files proved essential for preserving data integrity. Overall, this lab demonstrated how scripting with Python is a valuable tool for scalable access management and policy enforcement in cybersecurity environments.
