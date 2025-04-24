# POSOS NLP Challenge 

Ce projet a été réalisé dans le cadre du challenge de classification d’intentions médicales proposé par POSOS sur la plateforme ChallengeData.

## 📌 Objectif
Prédire l’intention médicale derrière chaque question posée en langage naturel (en français), parmi 50 classes.

## ⚙️ Modèles explorés
- Régression Logistique (baseline)
- XGBoost
- Modèle final : CamemBERT (transformer français)

## 📁 Structure
- `data/` : fichiers CSV d'entrée
- `data/output/` : fichiers de soumission
- `notebook/` : notebook d’analyse et modélisation
- `requirements.txt` : dépendances

## 🔧 Installation
```bash
pip install -r requirements.txt
