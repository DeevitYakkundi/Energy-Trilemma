# Energy-Trilemma  

A visualization dashboard for wholesale electricity markets in South Australia (SA) — exploring the trade-offs between sustainability, affordability, and reliability.

---

## 🚀 What is it

Energy-Trilemma analyses historical wholesale electricity market data for South Australia and produces interactive dashboards to illustrate how increasing variable renewable energy (wind + solar) affects:
- wholesale prices and price volatility (affordability)  
- renewable penetration and fossil-fuel displacement (sustainability)  
- residual demand and dependency on firm capacity (reliability / security)  

The dashboards are embedded via Tableau and provide insights into diurnal price patterns, seasonal trends, generation mix, and long-term shifts in the electricity system.

---

## 📄 Contents

- [Demo / Screenshots](#demo--screenshots)  
- [Data sources & Database](#data-sources--database)  
- [How to use / Run locally](#how-to-use--run-locally)  
- [How to embed/update dashboards](#how-to-embed-update-dashboards)  
- [Project structure](#project-structure)  
- [Team & Credits](#team--credits)  
- [License](#license)  

---

## Demo / Screenshots
<img width="1450" height="740" alt="image" src="https://github.com/user-attachments/assets/98fdce76-88fb-4635-a145-16f064717417" />

<img width="1494" height="761" alt="image" src="https://github.com/user-attachments/assets/2d159f6b-1a70-490d-b74a-ca32e2889b48" />

## Data sources & Database

The project uses open wholesale market data for South Australia. The main data sources / references are:

- **Open Electricity market data** — wholesale price, generation, demand, and renewable output for SA.  
- Processed local database / CSV files derived from the raw data, used for Tableau visualizations.  

You can find the processed data files inside the repo (e.g., `/data/`), or (if hosted elsewhere) a link to the database file / archive.  

---
## How to use / Run locally
Open the main HTML dashboard file (e.g., index.html) in your browser. The dashboards will load via embedded Tableau viz links.
---
## Team & Credits
This project was developed by:
Duy Trung Pham — david.pham@student.adelaide.edu.au
Deevit Deepak Yakkundi — deevitdeepak.yakkundi@student.adelaide.edu.au
Zac Horbelt — zac.horbelt@adelaide.edu.au
Special thanks to any data providers / open-data platforms used (e.g. Open Electricity).
