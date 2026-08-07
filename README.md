# Automotive Industry Strategic Analysis - 2030 Forecasts

## Demo

**[View Demo →](https://github.com/KaouechMaram/Automotive-Industry-Forecasting/releases/tag/v1.0.0)**

Access the interactive dashboards covering executive strategy, ML forecasting models, geographic analysis, and the 2030 electric vehicle transition.

---

## Project Overview

This project presents a comprehensive analysis of the global automotive industry, delivered as an interactive Streamlit application with 14 specialized analysis pages, forecasts through 2030, and strategic recommendations based on machine learning models.

---

## Analysis Pages

All pages are accessible from the sidebar of the Streamlit application.

### 1. Home
- **Description**: Project introduction and overview
- **Content**: Key metrics, production trends, yearly overview

### 2. Executive Dashboard
- **Description**: Strategic overview for senior management
- **Content**: Key performance indicators, 2030 scenario comparison
- **Audience**: Executive leadership, board of directors

### 3. Machine Learning Models
- **Description**: Comparative analysis of machine learning models
- **Content**: Model performance (R² scores), feature importance
- **Models**: XGBoost, Prophet, Linear Regression, ARIMA

### 4. Geographic Analysis
- **Description**: Regional analysis
- **Content**: Production trends and price comparison by region
- **Regions covered**: North America, Europe, Asia-Pacific, China

### 5. Electric Transition
- **Description**: Analysis of the transition to electric vehicles
- **Content**: EV share evolution, EV production by manufacturer

### 6. Manufacturers
- **Description**: Comparative analysis of major manufacturers
- **Content**: Production trends and average price by manufacturer
- **Manufacturers covered**: Toyota, Volkswagen, Ford, Hyundai-Kia, Stellantis, GM

### 7. Economic Analysis
- **Description**: Strategic economic analysis
- **Content**: Correlation with GDP growth, oil price impact on production

### 8. Competitive Intelligence
- **Description**: Competitive analysis and market positioning
- **Content**: Market share by manufacturer, market share evolution over time

### 9. Risks and Opportunities
- **Description**: Risk identification and analysis
- **Content**: Operational and regulatory risks, technological and market opportunities

### 10. Post-COVID Analysis
- **Description**: Pandemic impact and industry recovery
- **Content**: Monthly production trend 2020–2023, pre/post-COVID comparison

### 11. Advanced Electric Transition
- **Description**: In-depth analysis of the electric transition
- **Content**: EV share projections to 2030, battery cost evolution

### 12. Strategic Recommendations
- **Description**: Detailed strategic recommendations
- **Content**: Immediate and medium-term action plan, 2030 objectives

### 13. Sector Analysis
- **Description**: Analysis by sector and market segment
- **Content**: Production by vehicle category, margin analysis by segment

### 14. 2030 Outlook
- **Description**: Long-term vision and future scenarios
- **Content**: 2030 scenario comparison (radar chart), technology trends (autonomy, electrification)

---

## Usage

### 1. Install dependencies

```bash
pip install -r requirements_streamlit.txt
```

### 2. Launch the application

```bash
streamlit run streamlit_app.py
```

The app opens in your browser with a sidebar to navigate between all analysis pages: Home, Executive Dashboard, ML Models, Geographic Analysis, Electric Transition, Manufacturers, Economic Analysis, Competitive Intelligence, Risks and Opportunities, Post-COVID Analysis, Advanced Electric Transition, Strategic Recommendations, Sector Analysis, and 2030 Outlook.

---

## Project Structure

```
Automotive-Industry-Forecasting/
├── streamlit_app.py                     # Main Streamlit application
├── run_streamlit.py                     # Streamlit launcher script
├── requirements_streamlit.txt           # Streamlit app dependencies
├── regenerate_models.py                 # Script to retrain/regenerate ML models
│
├── code/                                # Analysis scripts
│   ├── automotive_analysis_main.py
│   ├── automotive_analysis_complete.py
│   ├── run_complete_analysis.py
│   ├── run_analysis.py
│   └── requirements.txt
│
├── dashboards/                          # 9 HTML dashboards
│   ├── dashboard_executif_direction.html
│   ├── dashboard_modeles_ml.html
│   ├── dashboard_analyse_geographique_avancee.html
│   ├── dashboard_transition_electrique.html
│   ├── dashboard_fabricants_automobile.html
│   ├── dashboard_analyse_economique_strategique.html
│   ├── dashboard_intelligence_concurrentielle.html
│   ├── dashboard_risques_opportunites.html
│   └── dashboard_principal_automobile.html
│
├── data/                                # Data and results
│   ├── comprehensive_automotive_data.csv
│   └── automotive_analysis_results_clean.json
│
├── models/                              # Saved ML models
│   ├── xgboost_production_clean.pkl
│   ├── xgboost_price_clean.pkl
│   ├── linear_regression_production_clean.pkl
│   ├── linear_regression_price_clean.pkl
│   ├── prophet_production_clean.pkl
│   └── arima_production_clean.pkl
│
└── README.md
```

---

## Features

### Specialized analyses
- Economic analysis: policy impact, costs, profitability
- Electric transition: EV adoption, infrastructure, government policies
- Risks and opportunities: risk matrix and mitigation measures
- Competitive intelligence: benchmarking and positioning

### Modeling
- Six machine learning models trained and validated
- Forecasts through 2030
- Multiple scenario analysis

### Visualizations
- 9 interactive HTML dashboards
- A unified Streamlit application with sidebar navigation
- Dynamic charts built with Plotly
- Interface adapted to different screen sizes

---

## Key Results

- **Best-case scenario**: accelerated electric vehicle transition (+10.4%)
- **Most influential factor**: raw material prices (28% importance)
- **Recommended approach**: gradual rather than abrupt transition
- **Electric vehicle opportunity**: estimated growth of 300% by 2030

### Strategic recommendations
1. Accelerate the electric transition gradually
2. Geographically diversify supply chains
3. Develop technology partnerships
4. Optimize production costs
5. Improve operational efficiency

---

## Documentation

- `README.md`: project guide
- Commented and documented source code

---

## Project Information

| Item | Detail |
|---|---|
| Analysis period | 2010-2023 (14 years) |
| Forecast horizon | 2024-2030 (7 years) |
| Data volume | 12,096 observations |
| Manufacturers covered | Toyota, Volkswagen, Ford, Hyundai-Kia, Stellantis, GM |
| Regions covered | North America, Europe, Asia-Pacific, China |
| Analysis pages | 9 dashboards + Streamlit app |
| Machine learning models | 6 models |

---

## Quick Start

```bash
# 1. Install Streamlit app dependencies
pip install -r requirements_streamlit.txt

# 2. Launch the application
streamlit run streamlit_app.py
```
