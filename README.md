# Inside Airbnb: Cape Town Analysis

## Project Overview
This project analyzes Airbnb listings in Cape Town to provide insights for hosts, travelers, and policymakers. Using data from Inside Airbnb, we aim to optimize pricing strategies, understand guest preferences, and assess the impact of Airbnb on the housing market.

## Business Problem
Cape Town's short-term rental market is competitive, with hosts seeking ways to maximize revenue and occupancy rates. Travelers need recommendations for the best locations and property types. Policymakers require insights into Airbnb’s influence on housing affordability and urban planning.

## Objectives
1. **Understand Market Trends**
   - Analyze the distribution of listings, pricing variations, and seasonal demand.
   - Identify factors influencing price differences across neighborhoods.

2. **Optimize Pricing Strategies for Hosts**
   - Discover factors contributing to higher occupancy rates.
   - Develop a dynamic pricing model based on demand patterns.

3. **Analyze Guest Preferences & Review Sentiment**
   - Extract key themes from guest reviews to determine satisfaction drivers.
   - Identify common complaints to improve hosting services.

4. **Assess Housing & Urban Planning Impact**
   - Examine Airbnb’s distribution across neighborhoods.
   - Investigate potential effects on housing availability and affordability.

5. **Enhance the Guest Experience**
   - Recommend ideal locations based on traveler needs (budget-friendly, luxury, family-friendly stays).
   - Suggest data-driven improvements in amenities and property features.

## Datasets Used
- **Summary Information & Metrics (Listings in Cape Town)** – Overview for visualizations, including pricing, occupancy rates, and property types.
- **Detailed Listings Data** – Insights into property characteristics, pricing, and availability trends.
- **Detailed Review Data** – Sentiment analysis of guest experiences and feedback.
- **Detailed Calendar Data** – Booking patterns, seasonality, and price fluctuations.
- **GeoJSON File of Neighborhoods** – Spatial analysis of Airbnb listings' impact on different areas.


## Dataset Handling Instructions
- The `user_reviews.csv` file is **not tracked by Git** to prevent large file issues. Ensure it is placed in the `Data/` folder before running sentiment analysis.
- To check if the dataset is ignored by Git, run:
  ```bash
  git check-ignore -v data/
  ```
- If the file is accidentally committed, remove it using:
  ```bash
  git rm -r --cached data/
  git commit -m "Stop tracking data directory"
  ```
- Consider using **Git LFS** for handling large files if necessary.

## Expected Outcomes
- A pricing recommendation system for Airbnb hosts.
- Insights into the best-performing neighborhoods for Airbnb investments.
- A sentiment analysis dashboard summarizing guest experiences.
- A visualization tool mapping Airbnb density and its effects on housing trends.

## Tools & Technologies
- **Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, NLTK)**
- **Jupyter Notebook**
- **GeoPandas for Spatial Analysis**
- **Tableau or Power BI for Visualization**

## Getting Started
### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `geopandas`, `nltk`

### Installation
Clone the repository and install dependencies:
```bash
pip install -r requirements.txt
```
## How to Run the Project
1. Clone the repository:
   ```bash
   git clone <repo_url>
   ```
2. Navigate to the project folder:
   ```bash
   cd Inside-Airbnb-Analysis
   ```
3. Ensure `user_reviews.csv` is placed in the `data/` folder.
4. Run Jupyter Notebook:
   ```bash
   jupyter notebook

### Running the Project
1. Load the dataset and perform exploratory data analysis (EDA).
2. Conduct sentiment analysis on guest reviews.
3. Develop predictive models for pricing and occupancy.
4. Visualize findings using Tableau, Power BI, or Matplotlib.

## Contributors
- Keziah Gicheha
- Contact: keziahgicheha@gmail.com

## License
This project is for educational purposes and follows the data usage policies of Inside Airbnb.

