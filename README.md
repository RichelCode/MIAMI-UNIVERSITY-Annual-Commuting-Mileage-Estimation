# MU Annual Commuting Mileage Estimation

**Affiliation:** Miami University, Oxford, Ohio  

---

## Project Overview
This project estimates the annual commuting mileage and associated CO₂ emissions for students, faculty, and staff at Miami University.  
It contributes directly to the university’s FY25 Climate Action Plan, focusing on **Scope 3 transportation emissions** and providing a reproducible baseline for future sustainability reporting.

---

## Objectives
- Estimate total annual commuting miles by group (students, faculty, staff)  
- Quantify average commuting distances using survey and ZIP code data  
- Calculate potential CO₂ emissions based on daily travel frequency and mode  
- Support the university’s sustainability team with transparent, reproducible analytics  

---

## Data and Methods
- **Data sources:**  
  - Miami University commuting survey results  
  - ZIP code distance tables and population counts  

- **Tools and libraries:**  
  - R, R Markdown, tidyverse, ggplot2, readxl, dplyr, lubridate  

- **Workflow summary:**  
  1. Cleaned and merged survey responses by commuter type  
  2. Estimated one-way and round-trip distances using ZIP code centroids  
  3. Scaled representative results to total population counts  
  4. Calculated annual mileage using average commute frequency and academic calendar days  
  5. Visualized results by group and generated an HTML sustainability report  

---

## Key Findings
- Faculty and staff account for the largest share of total commuting mileage due to consistent daily travel  
- Students show greater variation, mainly driven by off-campus housing distance  
- Combined results provide a university-wide baseline for tracking Scope 3 emissions  
- Outputs inform data-driven decision making in the FY25 Climate Action Plan  

---

## Deliverables
- Clean R Markdown analysis (`.Rmd`) and rendered HTML report  
- Figures summarizing total commuting miles and CO₂ emissions by category  
- Reproducible code for future annual updates  

---

## Skills Demonstrated
R Programming · R Markdown · Data Cleaning · Statistical Estimation · ggplot2 · Environmental Analytics · Sustainability Reporting · Collaboration · Data Visualization  

