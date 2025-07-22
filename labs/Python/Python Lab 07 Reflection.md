# Lab 07: Python Lists and Conditional Logic for Device Verification

- **Platform**: Google Cybersecurity Certificate  
- **Lab Focus**: Authenticating Users and Devices Using Python Lists and Conditionals

---

## 🧠 Overview

This lab focused on building a Python algorithm to authenticate users and verify that they are using their assigned devices. As a security analyst, verifying user identity and device authorization is a critical part of maintaining system integrity. The lab simulated a real-world security workflow where an analyst must determine if a user is approved to access the system and if they are using the correct device. Python lists and conditionals provided the tools to automate this verification process efficiently.

---

## ✅ Key Tasks Completed

- Used indexing to access user and device information stored in parallel lists  
- Applied the `.append()` method to add a new approved user and device to their respective lists  
- Used the `.remove()` method to delete a former employee and their device from the system  
- Wrote conditional statements to check if a username exists in the approved users list  
- Used the `.index()` method to locate the position of a username in the list and retrieve the corresponding device  
- Built logic to compare a user’s inputted device ID to the assigned device at the same index  
- Added an `elif` clause to distinguish between approved users with correct vs. incorrect devices  
- Defined a function `login(username, device_id)` that automated the entire user-device verification process with nested conditional logic  
- Tested the `login()` function with various username and device ID combinations to simulate different scenarios

---

## 💻 Technical Skills Practiced

- Working with parallel lists to associate related data  
- Adding and removing list elements using `.append()` and `.remove()`  
- Using conditional logic (`if`, `elif`, `else`) to control program flow  
- Locating list elements with `.index()` and using the result for cross-list referencing  
- Writing reusable Python functions with parameters  
- Implementing nested conditionals to handle multi-layered verification processes

---

## 🔁 Reflections

This lab highlighted how list operations and conditionals can be combined to solve practical security problems, such as verifying access credentials and device ownership. The ability to automate these checks through a function not only saves time but also reduces the potential for human error in repetitive verification tasks.

I found it rewarding to see how each small task—like appending to a list or using `.index()`—came together in the final function. This experience strengthened my confidence in Python's capability to support real-world cybersecurity workflows and showed how fundamental coding concepts can be used to enforce identity and access management protocols.
