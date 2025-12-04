# ${\textsf{\color{#E66C37}☄️ PowerBI Meteorite Landings Dashboard }}$ 
*A beginner-friendly journey from messy data → insights → a beautiful dashboard!*

---
<p align="center">
  <img width="2038" height="1130" alt="PowerBI Dashboard" src="https://github.com/user-attachments/assets/3c89f563-fda3-4d95-aa86-50a6705e9c54" />
</p>

## ${\textsf{\color{#2ED4D8}🌟 Project Overview  }}$ 
This project walks through the full data analysis workflow using a meteorite landing dataset (not NASA - just a provided data sheet!).  
I wanted to challenge myself to handle a semi-messy dataset, clean it with Python and create an interactive dashboard using Power BI.

If you're also learning data analytics, this repo is perfect inspiration for end-to-end projects.

---

## ${\textsf{\color{#2ED4D8}📁 What’s Inside This Repo?}}$ 
```bash
.
├── README.md
├── data
│   ├── Meteorite Exploration Data.xlsx
│   └── Processed Meteorite Exploration Data.csv
├── jupyter_notebook
│   └── Meteorite Exploration Data (Data Exploration & Cleaning Notebook).ipynb
└── ☄️ Meteorite Discoveries & Distribution Dashboard.pbix
```
### ${\textsf{\color{#EB895F}🔍 1. Data Exploration (Python)}}$
Using **Pandas**, I explored:
- Missing values  
- Outliers  
- Meteorite classes  
- Mass distribution  
- Geolocation points (reclat & reclong)  
- Fell vs Found categories  
- Decade of discovery

### ${\textsf{\color{#EB895F}🧹 2. Data Cleaning (Python)}}$

I cleaned the dataset by:
- Handling missing years  
- Converting year to **decade**  
- Creating binary formats for Fell/Found  
- Fixing mass values  
- Renaming + reordering columns  
- Creating helper columns like *log_mass*  

The cleaned dataset is included!

---

### ${\textsf{\color{#EB895F}📊 3. Power BI Dashboard (I used the web version)}}$
My dashboard highlights:
- Meteorite falls over time  
- Mass distributions  
- Meteorite classifications  
- Geographic locations  
- Fell vs Found comparisons  
- Insights I observed from the dataset  

Feel free to open the `.pbix` file and explore the visuals.

## ${\textsf{\color{#2ED4D8}🚀 How to Use This Repo}}$

### Option 1 — Just Explore  
Browse the notebooks, the cleaned CSV, and the dashboard.

### Option 2 — Run the Notebook 

### Option 3 — Open the .pbix file using Power BI Desktop.


## ${\textsf{\color{#2ED4D8}🧠 Key Learnings}}$

Some of the things I learned while building this project:
* How to handle real-world messy columns
* Why geolocation values matter (reclat & reclong)
* When to use log transformations
* How decade-based grouping improves trend analysis
* How to design clean dashboards with consistent themes


## ${\textsf{\color{#2ED4D8}🪐 Why Meteorites?}}$

Because meteorites are cool.
And if data is going to fall from the sky, you might as well visualize it.

## ${\textsf{\color{#2ED4D8}🤝 Contributions}}$

This is a beginner project - feedback, suggestions, or improvements are always welcome!
