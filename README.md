# STUDENT-REGISTRATION-SYSTEM
A comprehensive desktop application for managing student registrations in educational institutions. This system provides an intuitive interface for recording, storing, and retrieving student information along with parent details and profile pictures.
📋 Table of Contents
Overview

Features

Technologies Used

Installation

Usage Guide

Application Workflow

Database Structure

Screenshots

Contributing

License

📝 Overview
The Student Registration System is a desktop application built with Python's Tkinter library that streamlines the student enrollment process for universities and educational institutions. It offers a user-friendly interface for capturing comprehensive student data, storing it in Excel format, and managing profile pictures efficiently.

✨ Features
Core Functionalities
Automatic Registration Number Generation: System automatically assigns unique registration numbers to each student

Student Information Management: Capture detailed student information including name, class, gender, date of birth, religion, and skills

Parent/Guardian Details: Record parent names and occupations

Profile Picture Management: Upload and store student profile pictures

Search Functionality: Quick retrieval of student records using registration numbers

Update Records: Modify existing student information

Data Persistence: All data stored in Excel format for easy access and backup

User Interface Features
Clean and intuitive graphical interface

Color-coded sections for better organization

Real-time date stamping for registration

Form validation to prevent incomplete submissions

Responsive button controls

🛠 Technologies Used
Python 3.x: Core programming language

Tkinter: GUI framework for desktop application

Pillow (PIL): Image processing and handling

OpenPyXL: Excel file operations

Pathlib: File path management

Datetime: Date handling for registrations

💻 Installation
Prerequisites
Python 3.x installed on your system

pip package manager 
Setup Instructions
Clone the repository
git clone https://github.com/yourusername/student-registration-system.git
cd student-registration-system

pip install pillow
pip install openpyxl


mkdir "student images"

Prepare image assets

Place placeholder images in the appropriate directory

Update image paths in the code if needed (currently set to "C:/Users/ABC/Downloads/Image/")

Run the application
python student_registration.py

Image Storage
Profile pictures stored in "student images" folder

Naming convention: [Registration_Number].jpg
🙏 Acknowledgments
Thanks to all contributors and testers

Built for educational institutions to streamline student registration processes



Setup Instructions
Clone the repository
