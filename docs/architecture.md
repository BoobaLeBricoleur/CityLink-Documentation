# 🗂️ Architecture

La structure globale du projet est la suivante :


# Interface utilisateur 

(Nuxt) ├── CityLink-Front/ 

# API et logique métier 

(ExpressJS) ├── CityLink-Back/ 

# Backup de la base de données 

│ └── database.sql 

# Documentation complète (ce site)

└── CityLink-Documentation/ 

## Communication des requêtes

- **CityLink-Front** ↔️ HTTP API ↔️ **CityLink-Back**