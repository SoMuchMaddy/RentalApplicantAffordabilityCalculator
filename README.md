
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

-SoMuchMaddy/
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

# Sample Output

<img width="497" height="249" alt="image" src="https://github.com/user-attachments/assets/e8fae2f5-ab09-4a15-8d98-eef5691f6045" />

-----------------------------------------------------------------------------------------------------------------------------------

<img width="665" height="923" alt="image" src="https://github.com/user-attachments/assets/8b17b12b-8c1c-4144-bfb7-2778052e8923" />

-----------------------------------------------------------------------------------------------------------------------------------

<img width="223" height="198" alt="image" src="https://github.com/user-attachments/assets/0eee0266-fb50-4222-9bb7-f303beb7f8c7" />

-----------------------------------------------------------------------------------------------------------------------------------

<img width="343" height="1209" alt="image" src="https://github.com/user-attachments/assets/6edcb342-d32c-401c-9af5-b5de918ef654" />

-----------------------------------------------------------------------------------------------------------------------------------

<img width="602" height="1279" alt="image" src="https://github.com/user-attachments/assets/a1e10d3b-398d-4344-bcde-528c0fc99888" />

-----------------------------------------------------------------------------------------------------------------------------------

<img width="1087" height="1081" alt="image" src="https://github.com/user-attachments/assets/09667d1d-88b6-4680-be55-8d8ce470d9f8" />

-----------------------------------------------------------------------------------------------------------------------------------

<img width="219" height="189" alt="image" src="https://github.com/user-attachments/assets/eb12bac9-3931-4733-9727-f4824a808e51" />

-----------------------------------------------------------------------------------------------------------------------------------

<img width="630" height="387" alt="image" src="https://github.com/user-attachments/assets/67438ec0-5d14-43fa-bf34-e7f6758dabbc" />

---
## TXT Files

![image](https://github.com/user-attachments/assets/4d252c09-700b-496d-92e7-c4f7864142b1)
![image](https://github.com/user-attachments/assets/886be81f-73a5-45e8-aa7d-1e9870d9ae2c)
![image](https://github.com/user-attachments/assets/577d87ce-055a-4b8f-983d-d6cbbcfa4b0b)
![image](https://github.com/user-attachments/assets/315ba879-ba46-4566-9922-c6d74940862b)
![image](https://github.com/user-attachments/assets/63d5b2c7-5a87-4bb2-960b-bbb1db19a555)

## Example 1

![image](https://github.com/user-attachments/assets/90560876-ee0d-480d-99a8-ef7019fa9b84)
![image](https://github.com/user-attachments/assets/f24e3cef-a1b3-40c0-9954-603812a4ae08)

## Example 2

![image](https://github.com/user-attachments/assets/ed0a32f3-1f6b-49d6-8aba-eb1f41475020)
![image](https://github.com/user-attachments/assets/89dbd0bb-7a46-4dc8-9790-ea9cf85e1a1a)

## Example 3
![image](https://github.com/user-attachments/assets/e1291b63-f631-4bc0-8045-9e49cf2f473d)
![image](https://github.com/user-attachments/assets/f84028fb-c273-4059-a822-dea9b1b5b026)

