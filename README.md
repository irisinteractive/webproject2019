# Bienvenue dans la data visualisation.

Ce repository concentre des données ouvertes et exploitables (ASAP) qui pourront vous être utiles lors de la réalisation de votre projet web.

Vous trouverez deux répertoires distincts concernant deux sources de données différentes.

Les deux sources de données comporte la même arborescence de base, à savoir:

- `data_dictionnaries` --> Un fichier CSV par table (données et référentiel)
- `raws` --> Un fichier SQL par table

Voici un descriptif succint des sources de données

### MyBus

...

### eTourism

Les données que vous trouverez ici concerne le trafic d'un site de eTourisme (horodaté et catégorisé) en lien avec de la données touristiques géolocalisé (ASAP).

Ainsi, si vous vous référé aux dictionnaires des données, le fichier `data_dictionnary_touristic_object.csv` concentre la donnée touristique et le fichier `data_dictionnary_tracking_data.csv` concentre la donnée de tracking.

Le fichier `data_dictionnary_tracking_data_category.csv` concentre le référentiel des catégories "d'utilisation du site", cela permettant de contextualiser le trafic du site selon un horodatage.

Le fichier `data_dictionnary_touristic_object.csv` contient un champs `data` représentant les données de la page consulté, vous pouvez donc mettre en lien une donnée de tracking avec une donnée touristique via ces datas.

> Attention, les fichiers SQL en place dans le répertoire `raws` ne sont pas complets ni complètement exploitables, nous nous efforçons de vous fournir ces dernièrs le plus rapidement possible.

### Cycle de vie

Ce repository sera maintenu tout au long de l'année afin de fournir encore plus de données et de précisions.

Ce dernier est également ouvert, il vous est donc possible de déposer des issues afin de demander de plus amples informations, voir faire des demandes d'ajout / modification / suppression.

Faites des `pull` régulièrement pour profiter des dernières informations déposées !