# PROG101_ViccessSarahNyama_905005974
# Waste Billing System - PROG101

**Name:** VICCESS SARAH NYAMA  
**ID:** BSEM1101 / 905...  
**Course:** PROG101 - Introduction to Programming  
**Project:** Waste Billing Calculator (Flowgorithm)

### 1. Project Description
This program calculates waste disposal fees based on waste type and weight. It allows the user to calculate multiple bills in one run.

The system supports 3 waste types:
- **General Waste:** $5 per kg
- **Recyclable Waste:** $2 per kg
- **Hazardous Waste:** $15 per kg

This covers the requirement: [PASTE 2 SCREENSHOTS WITH _5_, _2, *15]

### 2. Files Included
1.  `Waste_Billing.fprg` - Main Flowgorithm flowchart file (contains Main + Calculatefee function)
2.  `pseudocode.txt` - Pseudocode for the system
3.  `README.md` - This file

### 3. Functions

#### a) Function Main()
- Declares variables: `again`, `wasteType`, `weight`, `fee`
- Loops while user enters "yes"
- Takes input for waste type and weight
- Calls Calculatefee function
- Displays total fee

#### b) Function Calculatefee(wasteType: String, weight: Real) : Real
- Input: wasteType and weight
- Processing: 
    - If general -> result = weight * 5
    - If recyclable -> result = weight * 2
    - If hazardous -> result = weight * 15
    - Else -> result = 0
- Output: Returns calculated fee

### 4. How to Run
1. Install Flowgorithm
2. Open `Waste_Billing.fprg`
3. Click Run (Green Play button)
4. Enter waste type: general / recyclable / hazardous
5. Enter weight in kg
6. View fee
7. Type "yes" to calculate another or "no" to exit

### 5. Pseudocode Summary
