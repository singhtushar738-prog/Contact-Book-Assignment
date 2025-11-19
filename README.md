# Contact Book Management System

**Student Name:** Tushar Singh
**Course:** MCA(AI/ML) 
**Subject:** Python Programming  
**Project Title:** File Handling Based Contact Book  
**Date:** Programming for Problem Solving Using Python
**Subject Code:** ETCCPP171

---

# Project Overview

This project is a Python-based **Contact Management System** that allows users to store, view, search, update, and delete contact information. The system uses **CSV** for primary data storage and supports exporting and loading data in **JSON** format. The project demonstrates file handling, exception management, and CRUD operations using Python.

---

# Features

| Feature | Description |
|--------|-------------|
| Add Contact | Allows users to input name, phone, and email and save to CSV |
| View Contacts | Reads and displays all contacts neatly in tabular output |
| Search Contact | Finds a contact by name and shows full details |
| Update Contact | Modify phone number or email of an existing contact |
| Delete Contact | Remove a contact from storage |
| Export to JSON | Converts all CSV contacts into JSON format |
| Load from JSON | Reads contacts from JSON and displays them |
| Error Logging (Bonus) | Logs errors with timestamp into `error_log.txt` |

---

# File Structure

contact_book/
│
├── contact_manager.py # Main program
├── contacts.csv # Stores contact data (auto generated)
├── contacts.json # JSON export file (generated when exporting)
└── error_log.txt # Stores error logs (auto generated if needed)
