
# Rental Applicant Affordability Calculator (RAAC) - Console-Based Applicant Evaluation System

RAAC is a full-featured console application designed to evaluate rental applicants based on financial criteria and property-specific costs. It supports detailed affordability analysis, input validation, file-based data management, and automated scoring to assist with rental decision-making.

---

# Project Description
RAAC helps property managers and landlords assess whether an applicant can reasonably afford a specific rental property by organizing and analyzing key financial and property data:

- Applicant income and debt tracking
- Debt-to-income ratio calculation
- Property selection via external data files
- Utility cost estimation based on property type, location, and size
- Yard care and additional expense calculations
- Overall affordability scoring system
- Optional detailed report generation (saved to file)
- Persistent property and utility data via structured text files

All interaction occurs through a menu-free, guided console interface using validated keyboard input, ensuring a smooth and error-resistant user experience.

---

# Dependencies & Installation  

RAAC requires:

- A Java compiler (Java 8 or higher)
- A terminal or command-line environnment
- Access to required data files (properties.txt and utility cost files)

Directory structure:

RAAC-SoMuchMaddy/
│

├── data/ ← All input data files (.txt)

└── terminal/ ← All Java source files (.java)

Setup Requirements:

Before running the program, ensure:
- All .txt files remain inside the data/ folder
- The program is executed from the correct working directory 

To compile:
cd terminal
javac *.java

To run:
java ApplicantChecker

**Note:** 
The application relies on external data files located in the data/ directory. If these files are moved or renamed, the program may fail to locate property or utility information.
All execution is console-based; no GUI is required.
Designed for use in standard terminal environments (Windows PowerShell, macOS Terminal, or Linux shell).

---

# Sample Text Files

![image](https://github.com/user-attachments/assets/4d252c09-700b-496d-92e7-c4f7864142b1)
![image](https://github.com/user-attachments/assets/886be81f-73a5-45e8-aa7d-1e9870d9ae2c)
![image](https://github.com/user-attachments/assets/577d87ce-055a-4b8f-983d-d6cbbcfa4b0b)
![image](https://github.com/user-attachments/assets/315ba879-ba46-4566-9922-c6d74940862b)
![image](https://github.com/user-attachments/assets/63d5b2c7-5a87-4bb2-960b-bbb1db19a555)

-----------------------------------------------------------------------------------------------------------------------------------

# Sample Output

Example 1

![image](https://github.com/user-attachments/assets/90560876-ee0d-480d-99a8-ef7019fa9b84)
![image](https://github.com/user-attachments/assets/f24e3cef-a1b3-40c0-9954-603812a4ae08)

-----------------------------------------------------------------------------------------------------------------------------------

Example 2

![image](https://github.com/user-attachments/assets/ed0a32f3-1f6b-49d6-8aba-eb1f41475020)
![image](https://github.com/user-attachments/assets/89dbd0bb-7a46-4dc8-9790-ea9cf85e1a1a)

-----------------------------------------------------------------------------------------------------------------------------------

Example 3

![image](https://github.com/user-attachments/assets/e1291b63-f631-4bc0-8045-9e49cf2f473d)
![image](https://github.com/user-attachments/assets/f84028fb-c273-4059-a822-dea9b1b5b026)

---

# Repository & Software Design

RAAC uses object-oriented design with the following major classes:

- ApplicantChecker – central controller class (handles input flow, calculations, and report generation)
- Property – stores property metadata including rent, type, location, and utilities
- DebtToIncome – encapsulates applicant income, debt, and ratio calculations
- Score (enum) – defines qualification tiers based on affordability thresholds

The program emphasizes:

- Encapsulation of financial and property data
- File-based persistent data loading (properties and utility configurations)
- Modular utility cost calculations via helper methods
- Use of arrays and file parsing for structured data processing
- Input validation loops for safe user interaction
- Clear separation between computation, I/O, and reporting logic  

---

# Javadoc Overview

The project includes detailed Javadoc for:

### **Classes**
- ApplicantChecker
- Property
- DebtToIncome
- Score (enum)

### **Methods**
- Constructor behavior for Property and DebtToIncome
- Accessors & mutators for all core data fields
- Property lookup and file parsing (propertyInfo)
- Utility cost calculation system (utilInfo, addUtils)
- Yard care cost estimation (yardCareCost)
- Debt-to-income and affordability calculations (moneyUse, leftOver)
- Score classification logic (returnScore)
- Report generation system (printReport)
- Input validation loops for all user prompts

### **Blocks of functionality explained**
- File parsing and property dataset loading
- Utility cost resolution by housing type and usage category
- Multi-step affordability scoring pipeline
- Report formatting and structured file output generation
- Input validation patterns for numeric and string-based inputs
- Exception handling for missing or malformed data files



---

# UML Class Diagram  

<img width="1936" height="2283" alt="StableMateUML" src="https://github.com/user-attachments/assets/29f29ad1-c189-4741-b82b-06ef7784c479" /> 

---

# Citations & Influences

- Inspiration for logic based on real equine management practices 

---
