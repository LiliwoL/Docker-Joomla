```
 ____             _                   _                       _       
|  _ \  ___   ___| | _____ _ __      | | ___   ___  _ __ ___ | | __ _
| | | |/ _ \ / __| |/ / _ \ '__|  _  | |/ _ \ / _ \| '_ ` _ \| |/ _` |
| |_| | (_) | (__|   <  __/ |    | |_| | (_) | (_) | | | | | | | (_| |
|____/ \___/ \___|_|\_\___|_|     \___/ \___/ \___/|_| |_| |_|_|\__,_|
```

# Accès

PHPMyAdmin
http://localhost:8181

MySQL
localhost:3306

App:
http://localhost:8080

---

# Lancement de la stack

`docker-compose up --env-file .env.docker -d`

---

# Joomla

Allez sur l'adresse:

On arrive sur la page d'installation de Joomla

![](readme_docs/9ef660d7.png)

Saisie des informations de connexion de l'administrateur

![](readme_docs/9dd28f00.png)

Saisie des informations de la base de données

![](readme_docs/13c303f0.png)

> Cf. le fichier .env.docker

Type: MySQL (PDO)
Hôte: joomladb
Utilisateur: joomla
Mot de passe: joomla
Base de données: joomla

![](readme_docs/1b37737a.png)

