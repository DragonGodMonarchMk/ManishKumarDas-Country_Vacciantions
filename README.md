# ManishKumarDas-Country_Vacciantions
This is a dataset about Vaccination Programs across the globe and also the number of Vaccinations done per million per and per thousands . 

# Global COVID-19 Vaccination Progress Analysis 🌍
Global COVID‑19 Vaccination Dashboard & Analysis – Built a reproducible data science pipeline in Python and Jupyter to explore the “country_vaccinations” dataset (covering ~190+ nations and daily metrics such as per‑million vaccination rates, people fully immunized, and vaccine types) 
GitHub,Kaggle. Developed interactive dashboards, maps (via Plotly Express and Folium), and time series trend analyses — including a dedicated India‑focused analysis notebook. Performed EDA, feature engineering, and temporal clustering to surface global inequality in vaccine roll‑out. Visualized policy impacts across demographics using income and WHO region groupings (~11 core variables per country) 
PMC. Published annotated notebooks with inline commentary and visual output on GitHub to emphasize transparency and shareable insight.
> Data-driven insights into COVID-19 vaccination rollouts across countries, with interactive visualizations and a deep dive into India’s drive.

---

## 🔢 Dataset Overview  
- ✅ **Source:** Kaggle “COVID-19 World Vaccination Progress”  
  Contains daily vaccination data (total vaccinations, people partially/completely vaccinated, doses per million, vaccine types, etc.) for ~190+ countries, compiled into a `country_vaccinations.csv` file :contentReference[oaicite:5]{index=5}.  
- 🔧 **Coverage:** ~11 attributes per record for each country; aggregated from reliable sources like WHO and national ministries :contentReference[oaicite:6]{index=6}.  
  Includes global classification categories such as income level, vaccine policy, and regional group.

---

## 🎯 Project Goals
| Objective | Description |
|-----------|-------------|
| **Exploratory Analysis** | Assess disparities in vaccine access and administration rates across WHO regions and income tiers. |
| **Visualization** | Generate world choropleths, trend graphs for “doses per million”, and time-series overlays for high and low GDP countries. |
| **Region-Specific Focus** | Deep dive into India’s vaccination trajectory including comparative rollout among states and by vaccine brand/type. |
| **Modeling (optional)** | Estimate future vaccination milestones using linear regression or moving average models where appropriate. |

---

## 📓 Notebooks & Content Highlights

| File | Description |
|------|-------------|
| `Country_Vaccinations.csv.ipynb` | Global EDA: trends over time, world ranking, vaccine-type distribution |
| `covid-19-vaccination-drive-india.ipynb` | India-specific analysis of total vaccinations, per million trends, peak rollout periods |
| `covid-19-world-vaccination-progress-visualization.ipynb` | Dashboard-style visuals using Plotly’s choropleth and animation features |

Additional resources: PDFs for executive summaries or slide presentations are included if you use them in project deliverables.

---

## 🧰 How to Run Locally

```bash
git clone https://github.com/DragonGodMonarchMk/ManishKumarDas-Country_Vacciantions.git
cd ManishKumarDas-Country_Vacciantions
python3 -m venv venv     # or conda create -n venv python=3.x
source venv/bin/activate

Country_Vacciantions/  
├── country_vaccinations.csv           ← Global vaccination dataset  
├── Country_Vaccinations.csv.ipynb     ← Full global EDA notebook  
├── covid-19-world-vaccination-progress-visualization.ipynb  
├── covid-19-vaccination-drive-india.ipynb  
├── covid-vaccination-doses-per-capita.png  
├── plots/                             ← Saved static visuals (PNG, HTML)  
├── outputs/                           ← CSVs or summary tables exported  
├── requirements.txt  
└── README.md                          ← This file  

🚀 Next Steps & Ideas
Develop forecasting models (e.g. ARIMA or LSTM) to estimate when countries may reach 70–80% population coverage.
Integrate vaccine hesitancy surveys or COVAX donation data to contextualize rollout speed.
Publish as an interactive Plotly Dash or Streamlit dashboard for policy makers.
Compare mortality reduction or case declines pre- and post-vaccine drives for causal insights.

📜 License & Acknowledgments
Dataset: Last updated May–July 2021, publicly licensed (CC BY‑NC‑SA 4.0 / subject to Kaggle's terms) 
GitHub
This code & analysis: Licensed under the MIT License

Repo owner: @DragonGodMonarchMk

Inspired by the work of Our World in Data and Kaggle community notebooks — attribution included in the analysis notebooks.

📊 Key Insights (example findings)
United States, China, and UK featured among the highest doses per million during early 2021; lower-middle income countries lagged significantly throughout 2020–21.
Israel and Seychelles reached >100% vaccination (based on doses per million) earliest globally.
In India, per‑million daily vaccination surged post-April 2021 with peak output in mid-2021; rural rollout caught pace during Phase … (insert your actual phases).
Broad access to Covishield and Covaxin after Q1/2021 contrasted with AstraZeneca/Pfizer dominance in developed countries.

✉️ Contributing & Feedback
Contributions welcome!
To suggest enhancements:
Fork this repo
Create a branch (feature/...)
Commit visuals, EDA, or scripts
Submit a pull request
pip install -r requirements.txt
jupyter notebook
