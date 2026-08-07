# Analyse Stratégique de l'Industrie Automobile - Prévisions 2030

## Aperçu du projet

Ce projet présente une analyse complète de l'industrie automobile mondiale, structurée en 16 pages d'analyses spécialisées, avec des prévisions jusqu'en 2030 et des recommandations stratégiques basées sur des modèles de machine learning.

---

## Pages d'analyses

### 1. Accueil
- **Fichier**: `dashboard_accueil.html`
- **Description**: Page d'introduction et présentation du projet
- **Contenu**: Objectifs, méthodologie, fabricants analysés, couverture géographique
- **Navigation**: Liens vers l'ensemble des autres pages

### 2. Dashboard exécutif
- **Fichier**: `dashboard_executif_direction.html`
- **Description**: Vue d'ensemble stratégique destinée à la direction
- **Contenu**: Indicateurs clés de performance, tendances
- **Public visé**: Direction générale, conseil d'administration

### 3. Modèles de machine learning
- **Fichier**: `dashboard_modeles_ml.html`
- **Description**: Analyse comparative des modèles de machine learning
- **Contenu**: Performance des modèles, comparaisons, métriques
- **Modèles**: XGBoost, Prophet, régression linéaire, ARIMA

### 4. Analyse géographique
- **Fichier**: `dashboard_analyse_geographique_avancee.html`
- **Description**: Analyse géographique par région
- **Contenu**: Performance par région, marchés émergents, dynamiques locales
- **Régions couvertes**: Amérique du Nord, Europe, Asie-Pacifique, Chine

### 5. Transition électrique
- **Fichier**: `dashboard_transition_electrique.html`
- **Description**: Analyse de la transition vers les véhicules électriques
- **Contenu**: Adoption des véhicules électriques, infrastructure, politiques publiques

### 6. Fabricants
- **Fichier**: `dashboard_fabricants_automobile.html`
- **Description**: Analyse comparative des principaux fabricants
- **Contenu**: Parts de marché, performance, positionnement stratégique
- **Fabricants couverts**: Toyota, Volkswagen, Ford, Hyundai-Kia, Stellantis, GM

### 7. Analyse économique
- **Fichier**: `dashboard_analyse_economique_strategique.html`
- **Description**: Analyse économique et stratégique
- **Contenu**: Impact des politiques publiques, coûts, rentabilité

### 8. Intelligence concurrentielle
- **Fichier**: `dashboard_intelligence_concurrentielle.html`
- **Description**: Analyse de la concurrence et du positionnement
- **Contenu**: Benchmarking, avantages concurrentiels

### 9. Risques et opportunités
- **Fichier**: `dashboard_risques_opportunites.html`
- **Description**: Identification et analyse des risques
- **Contenu**: Matrice de risques, opportunités, mesures de mitigation

### 10. Analyse post-COVID
- **Fichier**: `dashboard_analyse_post_covid.html`
- **Description**: Impact de la pandémie et reprise du secteur
- **Contenu**: Effets de la COVID-19, phase de récupération, nouvelles tendances

### 11. Transition électrique avancée
- **Fichier**: `dashboard_transition_electrique_avancee.html`
- **Description**: Analyse approfondie de la transition électrique
- **Contenu**: Technologies avancées, infrastructure, scénarios prospectifs

### 12. Recommandations stratégiques
- **Fichier**: `dashboard_recommandations_strategiques.html`
- **Description**: Recommandations détaillées pour l'orientation stratégique
- **Contenu**: Plan d'action, priorités, feuille de route

### 13. Analyse sectorielle
- **Fichier**: `dashboard_analyse_sectorielle.html`
- **Description**: Analyse par secteurs et segments de marché
- **Contenu**: Segments de marché, niches, spécialisation

### 14. Prospective 2030
- **Fichier**: `dashboard_prospective_2030.html`
- **Description**: Vision à long terme et scénarios futurs
- **Contenu**: Scénarios 2030, facteurs clés, vision stratégique

### 15. Dashboard principal
- **Fichier**: `dashboard_principal_automobile.html`
- **Description**: Vue d'ensemble intégrée
- **Contenu**: Ensemble des indicateurs clés, synthèse globale

### 16. Navigation principale
- **Fichier**: `dashboard_navigation.html`
- **Description**: Page de navigation centralisant l'accès aux analyses
- **Contenu**: Menu principal, accès rapide, statistiques générales

---

## Utilisation

### 1. Installation des dépendances
```bash
cd PROJET_AUTOMOBILE_FINAL/code/
pip install -r requirements.txt
```

### 2. Lancement de l'analyse complète
```bash
python run_complete_analysis.py
```

### 3. Accès aux dashboards
- Navigation: ouvrir `dashboards/dashboard_navigation.html`
- Accueil: ouvrir `dashboards/dashboard_accueil.html`
- L'ensemble des dashboards est disponible dans le dossier `dashboards/`

---

## Structure du projet

```
PROJET_AUTOMOBILE_FINAL/
├── code/                                # Scripts Python
│   ├── automotive_analysis_main.py
│   ├── automotive_analysis_complete.py
│   ├── run_complete_analysis.py
│   ├── run_analysis.py
│   └── requirements.txt
│
├── dashboards/                          # 16 dashboards HTML
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
├── data/                                # Données et résultats
│   ├── comprehensive_automotive_data.csv
│   └── automotive_analysis_results_clean.json
│
├── models/                              # Modèles ML sauvegardés
│   ├── xgboost_production_clean.pkl
│   ├── xgboost_price_clean.pkl
│   ├── linear_regression_production_clean.pkl
│   ├── linear_regression_price_clean.pkl
│   ├── prophet_production_clean.pkl
│   └── arima_production_clean.pkl
│
├── reports/                             # Rapports
│   ├── RAPPORT_COMPLET_ENCADREUR_*.pdf
│   └── automotive_analysis_report_clean.xlsx
│
├── README.md
└── README_COMPLET.md
```

---

## Fonctionnalités

### Analyses spécialisées
- Analyse post-COVID: impact de la pandémie et stratégies de reprise
- Transition électrique avancée: technologies, infrastructure, scénarios
- Recommandations stratégiques: plan d'action priorisé
- Analyse sectorielle: segmentation par segments de marché
- Prospective 2030: vision à long terme avec scénarios multiples

### Modélisation
- Six modèles de machine learning entraînés et validés
- Prévisions jusqu'en 2030
- Analyse de scénarios multiples

### Visualisations
- 16 dashboards HTML interactifs
- Graphiques dynamiques développés avec Plotly
- Navigation entre les pages
- Interface adaptée à différents formats d'écran

---

## Principaux résultats

- **Meilleur scénario**: transition vers les véhicules électriques accélérée (+10,4 %)
- **Facteur le plus déterminant**: prix des matières premières (28 % d'importance)
- **Approche recommandée**: transition progressive plutôt que brutale
- **Impact de la COVID-19**: reprise en V observée en 2021-2022
- **Opportunité liée aux véhicules électriques**: croissance estimée à 300 % d'ici 2030

### Recommandations stratégiques
1. Accélérer la transition électrique de manière progressive
2. Diversifier géographiquement les chaînes d'approvisionnement
3. Développer des partenariats technologiques
4. Optimiser les coûts de production
5. Améliorer l'efficacité opérationnelle

---

## Documentation

- `README_COMPLET.md`: guide complet du projet
- `README.md`: documentation d'origine
- `RAPPORT_COMPLET_ENCADREUR_*.pdf`: rapport destiné à l'évaluation académique
- Code source commenté et documenté

---

## Informations sur le projet

| Élément | Détail |
|---|---|
| Période d'analyse | 2010-2023 (14 ans) |
| Horizon de prévision | 2024-2030 (7 ans) |
| Volume de données | 12 096 observations |
| Fabricants couverts | Toyota, Volkswagen, Ford, Hyundai-Kia, Stellantis, GM |
| Régions couvertes | Amérique du Nord, Europe, Asie-Pacifique, Chine |
| Pages d'analyses | 16 dashboards |
| Modèles de machine learning | 6 modèles |

---

## Lancement rapide

```bash
# 1. Se placer dans le dossier du projet
cd PROJET_AUTOMOBILE_FINAL/code/

# 2. Installer les dépendances
pip install -r requirements.txt

# 3. Lancer l'analyse complète
python run_complete_analysis.py

# 4. La navigation s'ouvre automatiquement sur dashboard_navigation.html
```
