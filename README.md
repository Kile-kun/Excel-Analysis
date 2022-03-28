# Excel-Analysis


 # 1. OTD-ANALYSIS              
  </pre>
This Project (Dashboard) seeks to use the logistics manifest of a top Production company to establish relationships between its OTD and Some selected Features. 
Big thanks to Alex Freberg for the guidance.

## Screenshots
### 1. OTD Dashboard
https://raw.githubusercontent.com/Kile-kun/Excel-Analysis/main/OTD%20Dashboard.PNG

## Excel tools used:

  - Grouping of Quantities using IF statement (IF(B2>40, "40+ Tonnes", IF(B2>=30, "30-40 Tonnes", IF(B2>=20,"20-30 Tonnes",IF(B2>10,"10-20 Tonnes",IF(B2<=10,"0-10 Tonnes","Invalid")))))
  - Generation of  OTD compliance categories column from the calculated Delivery time (=IF(G2>36, "Excessively-Late Delivery", IF(G2>=22.8, "Mild-Late Delivery", IF(G2<=22.8, "Early Delivery","Late Delivery"))).
  - Creation of Pivots for tabular representation.
  - Generation Barcharts, Doughnut Charts and Line Chart.  
