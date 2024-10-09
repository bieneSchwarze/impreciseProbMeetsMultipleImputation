# Dummy data set
Created by Char Hilgers, 2024-10-09
Email: chilgers@diw.de
DIW Berlin, Socio-Economic Panel

## Data frame 
- Data frame with 7 variables, 44899 observations
- Inspired by the Socio-Economic Panel "pequiv" data set for the year 2019
- Saved in formats of .RData (preferred because it has correct column labels and value types) and European semicolon-separated .csv

## General information about Socio-Economic Panel
- "pequiv" data documentation: https://paneldata.org/soep-core/datasets/pequiv/

## Variables
**index**
- Simple index by row number

**labourearnings**
- Individual labour earnings in Euros
- Based on https://paneldata.org/soep-core/datasets/pequiv/i11110
- Previously imputed values set to missing
- Missing/invalid responses (coded as values <0 in documentation) set to missing

**age**
- Age in years
- Based on https://paneldata.org/soep-core/datasets/pequiv/d11101
- Missing/invalid responses (coded as values <0 in documentation) set to missing

**gender**
- Binary-only gender
- 1 is male, 2 is female
- Based on https://paneldata.org/soep-core/datasets/pequiv/d11102ll
- Missing/invalid responses (coded as values <0 in documentation) set to missing

**education**
- Education level with respect to high school
- 1 is less than high school, 2 is high school, 3 is more than high school
- Based on https://paneldata.org/soep-core/datasets/pequiv/d11108
- Missing/invalid responses (coded as values <0 in documentation) set to missing

**maritalstatus**
- Marital status:
  - 1 	Married
  - 2 	Single 
  - 3 	Widowed 
  - 4 	Divorced 	
  - 5 	Separated 	
  - 6 	Over 18 and NotW,Partnr6 (see documentation)
  - 7 	Under 18 And NotW,Partnr7 (see documentation)
- Married non-German "guest workers" whose spouses remained in their native countries are given a code of 6 or 7 depending on their ages
- Based on https://paneldata.org/soep-core/datasets/pequiv/d11104
- Missing/invalid responses (coded as values <0 in documentation) set to missing

**lifesatisfaction**
- Life satisfaction
- Scale from 0 to 10, where 0 is "Completely dissatisfied" and 10 is "Completely satisfied"
- Based on https://paneldata.org/soep-core/datasets/pequiv/p11101
- Missing/invalid responses (coded as values <0 in documentation) set to missing

