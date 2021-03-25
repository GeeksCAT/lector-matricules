# Lector de matricules
#### A partir d'imatges

De cara a afrontar el SmartCatalonia Challenge 2021 per facilitar la gestio d'afluencia en els parcs naturals, s'opta per una solucio d'un dispositiu que capti imatges o video, situat aprop de l'aparcament del parc natural, i que reconegui els vehicles aixi com les matricules.

Es treballa amb diversos pipelines:
* v1 - Proof of concept amb imatges estatiques
* v2 - Deteccio de matricules en videos
* v3 - Millora de la qualitat d'imatge per augmentar les deteccions positives
* v4 - Entrenar xarxa neuronal que aboqui resultats en temps real

A partir de tenir una xarxa entrenada que ho detecti, caldra averiguar si el hardware es capac de fer-la anar a >15fps i el consum que genera, sino caldra fer una v6 amb la xarxa neuronal retallada.
