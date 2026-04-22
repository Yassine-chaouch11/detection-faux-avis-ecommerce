# 🛡️ ReviewGuard - Enterprise NLP Fraud Analytics

> **Sécuriser la confiance dans l'e-commerce grâce à l'Intelligence Artificielle Explicable (XAI).**

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-lightgrey.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange.svg)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-purple.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

##  À propos du projet
Aujourd'hui, 89 % des consommateurs basent leur décision d'achat sur les avis en ligne. Cependant, 30 % des avis en ligne sont faux (générés par des fermes à clics), causant des pertes estimées à **152 milliards de dollars par an** selon le World Economic Forum.

**ReviewGuard** est un tableau de bord SaaS hybride conçu pour les équipes de modération (*Trust & Safety*). Il combine une extraction mathématique (TF-IDF) et une analyse lexicale (VADER) pour nourrir un modèle de **Régression Logistique optimisée**. Le résultat ? Une détection des fraudes avec une précision de **94.2%** (contre ~70% pour un humain seul), multipliant par 10 la productivité des modérateurs.

## Fonctionnalités Principales (SaaS B2B)
* **Moteur Hybride (LogReg + NLP) :** Combinaison de la vectorisation TF-IDF et de l'analyse d'intensité émotionnelle VADER.
* **Explicabilité Sémantique (White-Box AI) :** Le modèle n'est pas une "boîte noire". Il affiche visuellement les anomalies (positivité extrême, abus de majuscules, mots suspects) token par token pour justifier sa décision.
* **Tableau de Bord Dynamique :** Interface "Dark Mode" Enterprise, empreinte vectorielle sous forme de Radar Chart, et journal d'audit interactif de session.
* **Traitement de Masse (Import CSV) :** Scan de bases de données entières en un clic pour une intégration facile dans les workflows existants.
* **Temps Réel :** Temps d'analyse unitaire inférieur à 0.3 seconde.

##  Architecture Technique & Pipeline
L'application repose sur une architecture robuste et optimisée (Grid Search) :
* **Backend & Déploiement :** Python, Flask, Pandas, Werkzeug
* **Modèle Machine Learning :** Scikit-Learn (Régression Logistique)
* **Traitement du Langage (NLP) :** TF-IDF (5000 features), NLTK, VADER Lexicon, Regex
* **Frontend :** HTML5, CSS3, Bootstrap 5.3, JavaScript, Chart.js

## Méthodologie & Organisation (Agile)
Ce projet a été réalisé en 13 semaines par une équipe de 5 personnes, en appliquant les standards de l'industrie :
* **CRISP-DM :** De la compréhension du besoin métier jusqu'au déploiement Web.
* **Gestion de Projet Agile (Scrum) :** Découpage du travail en Sprints suivis sur **Jira**.
* **Collaboration CI/CD :** Versionnement strict, Pull Requests et résolution de conflits gérés sur **GitHub**.

##  Installation & Lancement en local

1. **Cloner le dépôt :**
   ```bash
   git clone [https://github.com/Yassine-chaouch11/detection-faux-avis-ecommerce.git](https://github.com/Yassine-chaouch11/detection-faux-avis-ecommerce.git)
   cd detection-faux-avis-ecommerce
