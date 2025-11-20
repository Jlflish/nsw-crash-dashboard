# Road Accidents in New South Wales (2020–2024)

## Project Overview
This project presents an interactive dashboard visualising the patterns of road accidents in New South Wales from **2020 to 2024**.  
It explores how accident numbers vary over time, by location (LGA), weather condition, and vehicle type.

The year 2019 was removed from the dataset to focus on recent data trends.  
A noticeable drop in 2021 accident counts was observed, likely related to **COVID-19 lockdowns** that reduced travel activity.

---

## File Summary

| File Name                                       | Description                                                                          |
| ----------------------------------------------- | ------------------------------------------------------------------------------------ |
| **index.html**                                  | The final interactive dashboard webpage. Can be opened directly in any web browser   |
| **build_embedded_dashboard.py**                 | Python script that constructs and exports the dashboard as an HTML file using Plotly |
| **main.py**                                     | Data preprocessing script that removes records where `Year of crash = 2019`          |
| **nsw_road_crash_data_2020-2024_crash.xlsx**    | Original dataset containing road crash records from 2019–2024                        |
| **nsw_road_crash_data_2020-2024_filtered.xlsx** | Cleaned dataset excluding 2019 data, used for generating the final dashboard.        |

---

## Instructions for Accessing or Using the Final Product

### Option 1 – Local Access
1. Download all project files to the same folder  
2. Open **index.html** in a modern web browser
3. Use the dropdown menus to filter data by **year**, **LGA**, **vehicle type**, or **weather condition**
4. All charts update automatically according to your selections

### Option 2 – Online Access
https://jlflish.github.io/nsw-crash-dashboard/
---

## A Copy of the Final Product
The file **index.html** is a read-only version of the dashboard and can be opened without additional software
A **screenshot** of the final dashboard layout is also provided in the submission ZIP for reference

---

## Source Components
All materials required to recreate this project are included:

- **Dashboard code:** `build_embedded_dashboard.py`  
- **Data cleaning script:** `main.py`  
- **Original and cleaned datasets:** Excel files included above  
- **Output product:** `index.html`  
- **Reference screenshot:** Included in ZIP  

---

## Data Processing Notes
- Removed all rows where `Year of crash = 2019`
- Observed drop in 2021 crash counts attributed to COVID-19 lockdowns
- No manual image editing (e.g., Photoshop, Illustrator) was performed
- Relative file paths are used so the project runs easily on other computers
