# Excel_CostumerComplaints_analysis
Project for FinServ Solutions.

## Project Objective

This project was developed for **FinServ Solutions** as an assignment within the Data Analytics Master by ProfessionAI. FinServ solutions is a company specializing in software solutions for managing customer complaints in the financial sector.  
The main goal is to enhance the effectiveness of customer complaint analysis by restructuring and customizing a spreadsheet. This will improve information access and better support decision-making processes.

---

## 💡 Motivation

FinServ identified several inefficiencies in the current spreadsheet used for complaint management. The main issues included:

- Difficulty in reading and interpreting the data
- Limited ability to extract meaningful insights
- Ineffective geographical analysis

A targeted reorganization of the spreadsheet will improve:

- Visibility of key information
- Speed in identifying issues
- Operational agility for the customer service team

---

## 🌟 Expected Added Value

- **Improved Geographical Analysis**:  
  A new dedicated tab enables the identification of areas with the highest number of complaints, supporting more targeted actions.

- **Enhanced Decision-Making**:  
  A statistical insights tab and data filtering features make it easier to identify the most frequent issues quickly and effectively.

- **Faster Response Times**:  
  The new structure highlights resolution times, improving performance monitoring and accountability.

---

## 🛠️ What Was Done

### First Tab – `Consumer complaints`

- **Style**:
  - Header row in **Comic Sans MS**, 12pt, blue, bordered on all 4 sides with a double line
  - Data cells bordered on all sides with a thin black line
  - Empty cells outside the table are white with no borders
  - Dates (`Date received` and `Date sent to company`) formatted as `dd/mm/yy`

- **Content**:
  - Final column calculates the number of days between sending and receiving
  - Rows sorted in ascending order by `Complaint ID`
  - A filter on `Date received` shows only records before `08/08/2016`

---

### Second Tab – `Geographical insights`

- **Style**:
  - Same formatting as the first tab
  - Header columns:
    - `Number of complaints per state`
    - `Percentage of complaints per state`

- **Content**:
  - Column A: state abbreviations (from the main tab)
  - Column B: complaint count per state (`=COUNTIF(...)`)
  - Column C: complaint percentage per state (rounded up)
    - **Conditional formatting**:
      - Green: < 2%
      - Red: ≥ 2%

---

### Third Tab – `Statistical insights`

- **Style**:
  - Same formatting as previous tabs
  - Header:
    - `Distinct issues`

- **Content**:
  - Column A: all unique complaint issues (from the `Issues` column in the main tab)
  - Cell `B7`: the **mode** value – the most frequent complaint category

---

## 📎 Tools & Technologies

- Microsoft Excel
- Formulas: `COUNTIF`, `MODE`, `FILTER`
- Conditional Formatting
- Data cleaning & visual organization

---

## 🧠 Skills Demonstrated

- Data cleaning and preparation
- Exploratory data analysis
- Visualization and structure for decision support
- Spreadsheet optimization for business workflows

---

## ✅ Outcome

An interactive and well-structured Excel file that enhances the efficiency of the complaint management process for the FinServ Solutions team.


