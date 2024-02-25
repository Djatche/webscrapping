# Webscrapping simple
Le webscrapping est une technique d'extraction de données de sites web par l'utilisation d'un script ou d'un orogramme. c'est souvent l'une des sources de données des organisations. Nous avions besoin des données sur les communes du Cameroun et leur type. L'information était disponible sur un site web à l'addresse https://fr.wikipedia.org/wiki/Commune_(Cameroun). Notre seul recours était d'extraire ces données par webscrapping. Voir image ci dessous.

![site_web_communes_cameroun](https://github.com/Djatche/webscrapping/assets/5621807/b5841ae4-0159-41af-bbaf-579d8a86bd80)


![site_web_communes_cameroun_2](https://github.com/Djatche/webscrapping/assets/5621807/d770d7bd-5ec5-4bc2-a8ed-03aebd644d80)

Après inspection de la page (script html), le tableau qui nous interesse est dans une balise "table" où l'attribut "class" a pour valeur "wikitable sortable centre".

![inspect page wik communes cameroun](C:\Users\hp\Documents\Projects\webscrapping\inspect1.PNG)

![inspect page wik communes cameroun](C:\Users\hp\Documents\Projects\webscrapping\inspect2.PNG)

Les données int été extraites et converties en dataframe puis sauvegardées sous fichier csv.
