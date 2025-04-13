## Author Profile:
Abdul Hadi - [hadiabdul13@gmail.com](hadiabdul13@gmail.com) | [LinkedIn](https://www.linkedin.com/in/abdul-hadi-447608159/)

# Airbnb Bangkok Analysis (2013–2022)
This project explores Airbnb listings in Bangkok using Python to uncover insights into occupancy rates, popularity, pricing strategies, and potential areas for listing expansion. It combines exploratory data analysis, statistical testing, and geospatial visualization.

## Objectives
- Understand the relationship between listing features and popularity
- Identify optimal pricing ranges based on room type and neighborhood
- Explore review patterns and their correlation with occupancy
- Recommend expansion opportunities in under-supplied high-demand areas

## Tools & Technologies
- Python (pandas, numpy)
- Data Visualization: seaborn, matplotlib
- Statistical Analysis: scipy, statsmodels (ANOVA, regression, Tukey HSD)
- Geospatial: folium (interactive maps)
- Jupyter Notebook

## Analysis Process
This project uses Airbnb listing data from Bangkok (uploaded in this repository) and follows a structured analysis pipeline:

- Understanding and exploring the dataset  
- Identifying and removing duplicate entries  
- Handling missing values  
- Detecting and eliminating outliers  
- Performing exploratory data analysis (EDA) to assess popularity and determine optimal pricing ranges  
- Running statistical tests, including both descriptive and inferential analysis  
- Drawing insights and conclusions from the findings

## Key Insights
- Listings with more reviews tend to have higher occupancy
- Entire homes and private rooms are more popular than shared/hotel rooms
- The best-performing listings are typically priced between 500–2,000 Baht
- High-demand neighborhoods like Huai Khwang, Nong Chok, and Bang Sue remain under-supplied
- Popularity and occupancy are closely tied to availability and host professionalism

## Map Visualizations
- Folium map shows listing distribution and price ranges by neighborhood
- Identifies top 6 neighborhoods for listing expansion based on high occupancy but low listing count

## How to Run
1. Clone the repository
2. Open `Airbnb_Analysis.ipynb` in Jupyter Notebook
3. Run cells from top to bottom or explore specific sections
4. Install required libraries if needed (`pip install -r requirements.txt`)

## Interactive Dashboard
Explore the interactive Tableau dashboard for a visual summary of the findings:

🔗 [Airbnb Bangkok Dashboard (Tableau)](https://public.tableau.com/app/profile/muhammad.abdul.hadi2799/viz/AirbnbDashboard_17439249214190/Dashboard1)

## License
This project is open-source and available under the MIT License.
