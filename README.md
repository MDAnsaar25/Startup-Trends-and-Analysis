   ---

# Startup Trends and Analysis

Analysis of global startup ecosystems, funding patterns, and failure/success factors using real-world datasets. Visualizes trends in investments, industries, and growth with Python (Pandas, Matplotlib, Seaborn).

### Overview
This project analyzes global startup trends, funding patterns, and success/failure factors using real-world datasets. It provides data-driven insights into which industries are growing, where funding is flowing, and what makes startups succeed or fail.

### Key Features
- Funding trend analysis by year, industry, and geography
- Success vs Failure factor analysis
- Investment stage-wise breakdown (Seed, Series A, B, C)
- Interactive visualizations and dashboards
- Year-over-year growth comparison

### Tech Stack
- *Language:* Python
- *Libraries:* Pandas, NumPy, Matplotlib, Seaborn, Plotly
- *Tools:* Jupyter Notebook, VS Code

### Dataset
- Source: Crunchbase / Kaggle Startup Dataset
- Fields: Company Name, Industry, Founded Year, Funding Amount, Funding Stage, Location, Status (Acquired/Closed/Operating)

### Key Insights Explored
1. Which industries received maximum funding in last 5 years?
2. Top startup hubs globally
3. Average funding by stage
4. Correlation between founding year and success rate
5. Common reasons for startup failure

### Installation & Usage
# Clone the repo
git clone https://github.com/your-username/Startup-Trends-and-Analysis.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook analysis.ipynb
### Visualizations
- Bar charts for industry-wise funding
- Line charts for funding trends over years
- Pie charts for funding stage distribution
- Heatmaps for geography vs investment

### Results
Found that Fintech, Healthtech, and AI/ML are leading in funding post-2020, with USA, India, and UK as top startup hubs. 90% of failed startups cited lack of market need and cash burn as key reasons.

### Future Scope
- Add predictive model for startup success prediction
- Build Streamlit dashboard
- Real-time data scraping from Crunchbase

---
*Author:* Mohamed Ansaar
*License:* MIT
