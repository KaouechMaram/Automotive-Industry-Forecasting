# Automotive Industry Strategic Analysis - 2030 Forecasts

## Demo

**[View Demo →](https://github.com/KaouechMaram/Automotive-Industry-Forecasting/releases/tag/v1.0.0)**

Access all 16 interactive dashboards covering executive strategy, ML forecasting models, geographic analysis, and the 2030 electric vehicle transition.
## Project Overview

This project presents a comprehensive analysis of the global automotive industry, structured into 16 specialized analysis pages, with forecasts through 2030 and strategic recommendations based on machine learning models.

---

## Analysis Pages

### 1. Home
- **File**: `dashboard_accueil.html`
- **Description**: Project introduction and overview
- **Content**: Objectives, methodology, manufacturers analyzed, geographic coverage
- **Navigation**: Links to all other pages

### 2. Executive Dashboard
- **File**: `dashboard_executif_direction.html`
- **Description**: Strategic overview for senior management
- **Content**: Key performance indicators, trends
- **Audience**: Executive leadership, board of directors

### 3. Machine Learning Models
- **File**: `dashboard_modeles_ml.html`
- **Description**: Comparative analysis of machine learning models
- **Content**: Model performance, comparisons, metrics
- **Models**: XGBoost, Prophet, Linear Regression, ARIMA

### 4. Geographic Analysis
- **File**: `dashboard_analyse_geographique_avancee.html`
- **Description**: Advanced regional analysis
- **Content**: Regional performance, emerging markets, local dynamics
- **Regions covered**: North America, Europe, Asia-Pacific, China

### 5. Electric Transition
- **File**: `dashboard_transition_electrique.html`
- **Description**: Analysis of the transition to electric vehicles
- **Content**: EV adoption, infrastructure, government policies

### 6. Manufacturers
- **File**: `dashboard_fabricants_automobile.html`
- **Description**: Comparative analysis of major manufacturers
- **Content**: Market share, performance, strategic positioning
- **Manufacturers covered**: Toyota, Volkswagen, Ford, Hyundai-Kia, Stellantis, GM

### 7. Economic Analysis
- **File**: `dashboard_analyse_economique_strategique.html`
- **Description**: Strategic economic analysis
- **Content**: Policy impact, costs, profitability

### 8. Competitive Intelligence
- **File**: `dashboard_intelligence_concurrentielle.html`
- **Description**: Competitive analysis and market positioning
- **Content**: Benchmarking, competitive advantages

### 9. Risks and Opportunities
- **File**: `dashboard_risques_opportunites.html`
- **Description**: Risk identification and analysis
- **Content**: Risk matrix, opportunities, mitigation measures

### 10. Post-COVID Analysis
- **File**: `dashboard_analyse_post_covid.html`
- **Description**: Pandemic impact and industry recovery
- **Content**: COVID-19 effects, recovery phase, emerging trends

### 11. Advanced Electric Transition
- **File**: `dashboard_transition_electrique_avancee.html`
- **Description**: In-depth analysis of the electric transition
- **Content**: Advanced technologies, infrastructure, forward-looking scenarios

### 12. Strategic Recommendations
- **File**: `dashboard_recommandations_strategiques.html`
- **Description**: Detailed strategic recommendations
- **Content**: Action plan, priorities, roadmap

### 13. Sector Analysis
- **File**: `dashboard_analyse_sectorielle.html`
- **Description**: Analysis by sector and market segment
- **Content**: Market segments, niches, specialization

### 14. 2030 Outlook
- **File**: `dashboard_prospective_2030.html`
- **Description**: Long-term vision and future scenarios
- **Content**: 2030 scenarios, key factors, strategic vision

### 15. Main Dashboard
- **File**: `dashboard_principal_automobile.html`
- **Description**: Integrated overview
- **Content**: All key indicators, overall synthesis

### 16. Main Navigation
- **File**: `dashboard_navigation.html`
- **Description**: Central navigation page for all analyses
- **Content**: Main menu, quick access, general statistics

---

## Usage

### 1. Install dependencies
```bash
cd PROJET_AUTOMOBILE_FINAL/code/
pip install -r requirements.txt
```

### 2. Run the full analysis
```bash
python run_complete_analysis.py
```

### 3. Access the dashboards
- Navigation: open `dashboards/dashboard_navigation.html`
- Home: open `dashboards/dashboard_accueil.html`
- All dashboards are available in the `dashboards/` folder

---

## Project Structure

```
PROJET_AUTOMOBILE_FINAL/
├── code/                                # Python scripts
│   ├── automotive_analysis_main.py
│   ├── automotive_analysis_complete.py
│   ├── run_complete_analysis.py
│   ├── run_analysis.py
│   └── requirements.txt
│
├── dashboards/                          # 16 HTML dashboards
│   ├── dashboard_navigation.html
│   ├── dashboard_accueil.html
│   ├── dashboard_executif_direction.html
│   ├── dashboard_modeles_ml.html
│   ├── dashboard_analyse_geographique_avancee.html
│   ├── dashboard_transition_electrique.html
│   ├── dashboard_fabricants_automobile.html
│   ├── dashboard_analyse_economique_strategique.html
│   ├── dashboard_intelligence_concurrentielle.html
│   ├── dashboard_risques_opportunites.html
│   ├── dashboard_analyse_post_covid.html
│   ├── dashboard_transition_electrique_avancee.html
│   ├── dashboard_recommandations_strategiques.html
│   ├── dashboard_analyse_sectorielle.html
│   ├── dashboard_prospective_2030.html
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
├── reports/                             # Reports
│   ├── RAPPORT_COMPLET_ENCADREUR_*.pdf
│   └── automotive_analysis_report_clean.xlsx
│
└── README.md
```

---

## Features

### Specialized analyses
- Post-COVID analysis: pandemic impact and recovery strategies
- Advanced electric transition: technologies, infrastructure, scenarios
- Strategic recommendations: prioritized action plan
- Sector analysis: market segmentation
- 2030 outlook: long-term vision with multiple scenarios

### Modeling
- Six machine learning models trained and validated
- Forecasts through 2030
- Multiple scenario analysis

### Visualizations
- 16 interactive HTML dashboards
- Dynamic charts built with Plotly
- Cross-page navigation
- Interface adapted to different screen sizes

---

## Key Results

- **Best-case scenario**: accelerated electric vehicle transition (+10.4%)
- **Most influential factor**: raw material prices (28% importance)
- **Recommended approach**: gradual rather than abrupt transition
- **COVID-19 impact**: V-shaped recovery observed in 2021-2022
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
- `RAPPORT_COMPLET_ENCADREUR_*.pdf`: report for academic evaluation
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
| Analysis pages | 16 dashboards |
| Machine learning models | 6 models |

---

## Quick Start

```bash
# 1. Navigate to the project folder
cd PROJET_AUTOMOBILE_FINAL/code/

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the full analysis
python run_complete_analysis.py

# 4. Navigation opens automatically at dashboard_navigation.html
```
## 🚀 Demo

👉 **[View Demo →](https://github.com/KaouechMaram/Automotive-Industry-Forecasting/releases/tag/v1.0.0)**

Explore the 16 interactive dashboards covering:
- 📊 Executive & strategic analysis
- 🤖 Machine learning models and forecasts
- 🌍 Geographic and market analysis
- ⚡ Electric vehicle transition
- 🔮 2030 scenarios and strategic recommendations
