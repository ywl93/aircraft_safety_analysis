# Phase 1 Project: Yi-Wei Liu

## Overview and Business Understanding
In this project, a hypothetical company (the "Company") is expanding into the business of operating aircraft for enterprises. The company would like to identify aircraft with the best safety record. For the purposes of this project, I define "best safety record" as having the lowest ratio of accidents involving fatal injuries to total number of accidents.

For this project, I will focus only on the aircraft manufacturer and not on specific aircraft models. The Company is seeking a long-term vendor to be a reliable supplier across a range of model types.

I will also answer the following business questions:

1) Location: Does the safety record vary between flights in the United States vs. overseas?
2) Purpose: Does the safety record vary between aircraft for personal and commercial use?
3) Weather: Is bad weather a major factor in causing fatal accidents?
   
The main documents in this repository include:  
1) this README file;
2) the non-technical presentation summarizing the conclusions to company's management ([presentation.pdf][https://github.com/ywl93/dsc-phase-1-project-v3/blob/master/presentation.pdf);
3) the Jupyter notebook showing the data preparation and analysis ([student.ipynb](https://github.com/ywl93/dsc-phase-1-project-v3/blob/master/student.ipynb));  
4) the Tableau dashboard with 3 visualizations corresponding to the 3 business questions ([tableau_dashboard.pdf](https://github.com/ywl93/dsc-phase-1-project-v3/blob/master/tableau_dashboard.pdf))

## Data Analysis and Conclusions
In short, Boeing is overall the manufacturer with the best safety record. Only 28% (461 of 1,675) of Boeing's accidents involved a fatal injury, vs. 50% (10,860 of 21,560) for all manufacturers ex-Boeing.

### 1) Location:  
Across all manufacturers, 48% of U.S. flight accidents involved a fatal injury vs. 52% of overseas flights.
Within U.S. flights, 39% (233 of 595) of Boeing's accidents involved a fatal injury, vs. 48% (9,408 of 19,423) for all manufacturers ex-Boeing.
Within overseas flights, it was 21% (228 of 1,080) for Boeing vs. 68% (1,452 of 2,137) for others.

Recommendation:
There is only a slightly higher safety risk overseas compared to the U.S.
If the Company decides it is commercially feasible to operate overseas, I recommend Boeing as the only manufacturer safe enough for overseas flights. For domestic flights, Boeing is still the best choice, but other manufacturers such as Robinson and Air Tractor are not far behind.
An avenue for further inquiry is why the fatal injury ratio for Boeing is much lower overseas than in the U.S. (21% vs 39%).

### 2) Purpose:  
Across all manufacturers, 48% (3,389 of 7,057) of commercial aircraft accidents involved a fatal injury vs. 49% for personal aircraft (7,932 of 16,178).
Within commercial flights, 27% (418 of 1,545) of Boeing's accidents involved a fatal injury vs. 54% (2,971 of 5,512) for all manufacturers ex-Boeing.
Within personal flights, it was 33% (43 of 130) for Boeing vs. 49% (7,889 of 16,048) for others.

Recommendation:
The safety risk for commercial and personal aircraft are similar. The Company may operate both types of aircraft depending on commercial feasibility. Boeing is the safest option for both.

### 3) Weather:  
Across all 23,235 accidents, 82% involved decent weather and 6% involved poor weather; weather for 12% of accidents were unknown.
Across 11,321 accidents with a fatal injury, 80% involved decent weather and 10% involved poor weather; weather for 10% were unknown.
In decent weather, 48% of all accidents involved a fatal injury. In poor weather, 81% of accidents involved a fatal injury.

Recommendation
In poor weather, the fatal injury rate was significantly higher than average. I would recommend our company not to operate aircraft in poor weather to reduce the risk of fatal injuries.
