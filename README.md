# LBD — Système hybride éolien-solaire pour le dessalement

Gestion intelligente d'un système d'énergie hybride (éolien + solaire + réseau) alimentant une unité de dessalement, avec un agent d'apprentissage par renforcement (Q-learning) qui optimise l'allocation d'énergie selon le coût et les émissions de CO₂.

## Contenu

- `Notebooks/` — prétraitement des données, requêtes API météo, modèle RL, MPC, simulation
- `Utils/` — environnement, agent Q-learning, stratégie naïve, sauvegarde/chargement et tests de l'agent
- `Interface/` — tableau de bord web (voir `Interface/README.md`)
- `Montage/` — scripts Raspberry Pi (capteurs, relais, calibration) et guides de branchement
- `Data/` — jeux de données météo et de production
- `models/` — agent entraîné (`q_agent_model.pbz2`)
- `Visuals 1.0/`, `visuals 2.0/` — résultats et graphiques

## Lancement

```bash
pip install flask flask-cors requests numpy pandas
python app.py
```

## Auteur

**KOURAI YOUSSEF** — kouraiyoussef@gmail.com

## Licence

MIT — voir [LICENSE](LICENSE).
