# Automotive Industry Strategic Analysis - 2030 Forecasts

## Demo

**[View Demo →](https://github.com/KaouechMaram/Automotive-Industry-Forecasting/releases/tag/v1.0.0)**

Access the interactive dashboards covering executive strategy, ML forecasting models, geographic analysis, and the 2030 electric vehicle transition.

---

## Project Overview

This project presents a comprehensive analysis of the global automotive industry, structured into 9 specialized analysis pages, with forecasts through 2030 and strategic recommendations based on machine learning models. The project also includes a Streamlit application that brings all analyses together in a single interactive interface.

---

## Analysis Pages

### 1. Executive Dashboard
- **File**: `dashboard_executif_direction.html`
- **Description**: Strategic overview for senior management
- **Content**: Key performance indicators, trends
- **Audience**: Executive leadership, board of directors

### 2. Machine Learning Models
- **File**: `dashboard_modeles_ml.html`
- **Description**: Comparative analysis of machine learning models
- **Content**: Model performance, comparisons, metrics
- **Models**: XGBoost, Prophet, Linear Regression, ARIMA

### 3. Geographic Analysis
- **File**: `dashboard_analyse_geographique_avancee.html`
- **Description**: Advanced regional analysis
- **Content**: Regional performance, emerging markets, local dynamics
- **Regions covered**: North America, Europe, Asia-Pacific, China

### 4. Electric Transition
- **File**: `dashboard_transition_electrique.html`
- **Description**: Analysis of the transition to electric vehicles
- **Content**: EV adoption, infrastructure, government policies

### 5. Manufacturers
- **File**: `dashboard_fabricants_automobile.html`
- **Description**: Comparative analysis of major manufacturers
- **Content**: Market share, performance, strategic positioning
- **Manufacturers covered**: Toyota, Volkswagen, Ford, Hyundai-Kia, Stellantis, GM

### 6. Economic Analysis
- **File**: `dashboard_analyse_economique_strategique.html`
- **Description**: Strategic economic analysis
- **Content**: Policy impact, costs, profitability

### 7. Competitive Intelligence
- **File**: `dashboard_intelligence_concurrentielle.html`
- **Description**: Competitive analysis and market positioning
- **Content**: Benchmarking, competitive advantages

### 8. Risks and Opportunities
- **File**: `dashboard_risques_opportunites.html`
- **Description**: Risk identification and analysis
- **Content**: Risk matrix, opportunities, mitigation measures

### 9. Main Dashboard
- **File**: `dashboard_principal_automobile.html`
- **Description**: Integrated overview
- **Content**: All key indicators, overall synthesis

---

## Usage

There are two ways to explore the analysis: the standalone HTML dashboards, or the interactive Streamlit application.

### Option A — Streamlit application (recommended)

```bash
# 1. Install dependencies
pip install -r requirements_streamlit.txt

# 2. Launch the app
streamlit run streamlit_app.py
```

The app opens in your browser with a sidebar to navigate between all analysis pages.

### Option B — Static HTML dashboards

```bash
# 1. Install dependencies
cd code/
pip install -r requirements.txt

# 2. Run the full analysis (regenerates data/models if needed)
python run_complete_analysis.py
```

Then open any file directly in your browser, for example:
- `dashboards/dashboard_principal_automobile.html`
- `dashboards/dashboard_executif_direction.html`
- All dashboards are available in the `dashboards/` folder

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
