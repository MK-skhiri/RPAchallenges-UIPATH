# 🤖 UiPath RPA Project – Automation Challenges

This repository contains two RPA workflows built with **UiPath** to automate real-world tasks inspired by popular RPA challenges. 

---
## 📌 Prerequisites

- UiPath Studio 
- Installed dependencies:
  - `UiPath.Excel.Activities`
  - `UiPath.System.Activities`
  - `UiPath.Testing.Activities`
  - `UiPath.UIAutomation.Activities`
- Microsoft Excel (for Excel-related activities)
- UiPath browser extension installed (for web automation)

---

## 📁 Project Structure

RPAchallenges-UIPATH/
├── Dependencies(windows)/
│ ├── UiPath.Excel.Activities=2.24.4
│ ├── UiPath.System.Activities=25.2.1
│ ├── UiPath.Testing.Activities=24.10.4
│ ├── UiPath.UIAutomation.Activities=24.10.12
│
├── ChallengesWorkflows/
│ ├── DataAutoGeneration.xaml
│ ├── InputFormsChallenge.xaml
│ ├── InputFormsChallenge-AutoGenData.xaml
│ ├── RPAstockMarketChallenge.xaml
│
├── Files/
│ ├── challenge.xlsx
│ ├── RPAinputdata.xlsx
│ ├── RPAmarket.xlsx
└── README.md
---

## 1️⃣ Input Forms Automation

### 🎯 Objective

Automate the process of filling out and submitting input forms on a challenge website using:

- Randomly generated data (first name, email, etc.)
- Structured data from Excel files

### 🔧 Tools & Technologies

- **UiPath Studio** and **Browser Automation (24.10)**
- Excel and Web automation activities

### 📂 Workflow Descriptions

- `DataAutoGeneration.xaml`: Generates random data for the form fields.
- `InputFormsChallenge.xaml`: Reads form input data from `Files/challenge.xlsx` and submits each entry.
- `InputFormsChallenge-AutoGenData.xaml`: Reads data from `Files/RPAinputdata.xlsx` and automates form submission.
- `RPAstockMarketChallenge.xaml`: Navigates to a stock market website, extracts stock data for 3 companies, and saves the results.

### 📸 Challenge Link

- [RPA Challenge - Input Forms](https://www.rpachallenge.com/)

---

## ▶️ How to Run the Workflows

1. Open the project in **UiPath Studio**.
2. Make sure the UiPath browser extension is installed and enabled.
3. Open any `.xaml` file and click **Run** or **Debug** in UiPath Studio.
4. Adjust file paths if needed (for example, Excel input files).


