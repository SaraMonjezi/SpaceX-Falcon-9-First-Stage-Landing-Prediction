# SpaceX Falcon 9 First Stage Landing Prediction

IBM Data Science Professional Certificate — Applied Data Science Capstone

**GitHub Repository URL:** https://github.com/SaraMonjezi/SpaceX-Falcon-9-First-Stage-Landing-Prediction

## Project Files

| File | Description |
|---|---|
| `jupyter_labs_spacex_data_collection_api_v2 (1).ipynb` | Data collection via the SpaceX REST API v4 |
| `jupyter_labs_webscraping.ipynb` | Wikipedia web scraping with BeautifulSoup (if present) |
| `labs_jupyter_spacex_Data_wrangling_v2 (1).ipynb` | Data wrangling, missing-value imputation, target class creation |
| `jupyter_labs_eda_sql_coursera_sqllite.ipynb` | Exploratory Data Analysis with SQL (SQLite) |
| `lab_jupyter_launch_site_location_v2.ipynb` | Interactive geospatial analysis with Folium |
| `spacex_dash_app.py` | Interactive Plotly Dash dashboard (launch site dropdown, payload range slider, pie chart, scatter chart) |
| `spacex_launch_dash.csv` | Dataset used by the Plotly Dash dashboard |
| `screenshot_1_all_sites.png` | Dashboard screenshot — all launch sites selected |
| `screenshot_2_ksc_site.png` | Dashboard screenshot — KSC LC-39A selected |
| `SpaceX_Machine_Learning_Prediction_Part_5_v1.ipynb` | Predictive analysis / classification models |
| `SpaceX_Falcon9_Landing_Prediction_Report.pdf` | Final presentation (all required sections) |

## Summary

This project predicts whether the Falcon 9 first stage will land successfully, using
data collected via the SpaceX API and Wikipedia, exploratory analysis (visual + SQL),
interactive Folium and Plotly Dash dashboards, and four tuned classification models
(Logistic Regression, SVM, Decision Tree, KNN). The best models reached 83.33% holdout
test accuracy with 100% recall on successful landings.
