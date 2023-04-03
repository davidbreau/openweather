# openweather

Projet : Récupération et analyse de données météorologiques pour 20 villes françaises

Dans ce projet, nous avons utilisé l'API OpenWeatherMap pour récupérer et analyser les données météorologiques de 20 villes françaises. Nous avons utilisé la librairie Requests pour faire des requêtes HTTP (GET) et récupérer les informations souhaitées.
Les informations récupérées

Nous avons récupéré les informations actuelles pour chaque ville, à savoir :

    Température actuelle
    Température ressentie
    Température minimale et maximale
    Pression atmosphérique
    Humidité
    Vitesse du vent
    Direction du vent
    Lever du soleil (converti en information compréhensible pour un humain)
    Coucher du soleil (converti en information compréhensible pour un humain)

Nous avons stocké ces informations dans un DataFrame (pandas) que nous avons ensuite exporté dans un fichier CSV.

Comment exécuter le code

    Cloner le repo GitHub.
    Installer les dépendances : pip install -r requirements.txt.
    Créer un fichier .env contenant la clé API OpenWeatherMap.
    Exécuter le notebook Jupyter weather.ipynb.
    Le fichier CSV OpenWeather_20_Villes_Francaises.csv contenant les informations météorologiques pour chaque ville sera généré.