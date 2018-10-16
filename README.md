# Bienvenue dans la data visualisation.

Ce repository concentre des données ouvertes et exploitables (ASAP) qui pourront vous être utiles lors de la réalisation de votre projet web.

Vous trouverez deux répertoires distincts concernant deux sources de données différentes.

Les deux sources de données comporte la même arborescence de base, à savoir:

- `data_dictionnaries` --> Un fichier CSV par table (données et référentiel)
- `raws` --> Un fichier SQL par table

Voici un descriptif succint des sources de données

### MyBus

Les données que vous trouverez pour ce projet concerne les différentes remontée d'informations de l'application **MyBus**.

Ainsi, si vous vous référez aux dictionnaires des données, le fichier `api_form_datas.csv` concentre la donnée utilisateur et le fichier `mybus_historique.csv` concentre la donnée de tracking de bus.

Toutes les données présentes dans les fichiers SQL sont horodatées et géolocalisées.

> Attention, les fichiers SQL en place dans le répertoire `raws` ne sont qu'un aperçu de vraies données, nous nous efforçons de vous fournir ces dernières le plus rapidement possible.

### eTourism

Les données que vous trouverez ici concerne le trafic d'un site de eTourisme (horodaté et catégorisé) en lien avec de la données touristiques géolocalisé (ASAP).

Ainsi, si vous vous référez aux dictionnaires des données, le fichier `data_dictionnary_touristic_object.csv` concentre la donnée touristique et le fichier `data_dictionnary_tracking_data.csv` concentre la donnée de tracking.

Le fichier `data_dictionnary_tracking_data_category.csv` concentre le référentiel des catégories "d'utilisation du site", cela permettant de contextualiser le trafic du site selon un horodatage.

Le fichier `data_dictionnary_touristic_object.csv` contient un champs `data` représentant les données de la page consulté, vous pouvez donc mettre en lien une donnée de tracking avec une donnée touristique via ces datas.

> Attention, les fichiers SQL en place dans le répertoire `raws` ne sont pas complets ni complètement exploitables, nous nous efforçons de vous fournir ces dernières le plus rapidement possible.

### Cycle de vie

Ce repository sera maintenu tout au long de l'année afin de fournir encore plus de données et de précisions.

Ce dernier est également ouvert, il vous est donc possible de déposer des issues afin de demander de plus amples informations, voire faire des demandes d'ajout / modification / suppression.

Faites des `pull` régulièrement pour profiter des dernières informations déposées !