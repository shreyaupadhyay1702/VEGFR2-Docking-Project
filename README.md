# VEGFR2-Docking-Project
Molecular docking and analysis of phytochemicals targeting VEGFR-2

## About the Project
This project was done to identify potential phytochemical compounds targeting VEGFR-2 using molecular docking.

## What I Did

- Selected 25 phytochemicals from literature based on two medicinal plants  (Sonneratia alba , Aeginetia indica)
- Stored and filtered data using SQLite  

- Applied basic drug-likeness filters:
  - Molecular weight  
  - LogP  
  - H-bond donor and acceptor  

- Filtered compounds from 25 to 13  

- Performed blind docking of 13 compounds using PyRx  
- Selected top 5 compounds based on docking score  

- Performed site-specific docking for the top 5 compounds  
- Observed that results were consistent with blind docking  

- Visualized interactions:
  - 2D interactions using Discovery Studio  
  - 3D structures using PyMOL  

## Tools Used
- PyRx  
- Discovery Studio  
- PyMOL  
- SQLite
- Excel 
## Conclusion
The study helped in identifying potential compounds that show good binding with VEGFR-2 and can be further explored.
