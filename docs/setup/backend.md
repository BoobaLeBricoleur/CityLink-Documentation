# 🔧 Installation Backend

## Cloner le repository

```bash
git clone https://github.com/BoobaLeBricoleur/citylink-back.git
cd citylink-back

Lancer avec Docker

docker-compose up -d

Importer la base de données

Le fichier SQL (database.sql) se trouve à la racine du projet backend.

Importez-le via :

    PhpMyAdmin

    ou votre IDE préféré

Les identifiants se trouvent dans le fichier docker-compose.yml.
Notes importantes

    Vérifiez que les ports nécessaires (MySQL, PhpMyAdmin) soient libres avant de lancer Docker.

    Assurez-vous que votre fichier .env est configuré correctement (voir Exemple fichier d'environnement).