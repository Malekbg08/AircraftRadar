# AircraftRadar
## Ben Ghachem Malek

## Project setup
```
python3 -m http.server
```

## Disclaimer
A noter qu'il faut appuyer sur Long Lat pour pouvoir switcher de type de visualisation.

Ex: Pour voir l'histogramme par rapport au temps, cliquez sur Long Lat puis Traffic Histogram. Même chose si vous ajustez les sliders en étant sur une visualisation autre que Longitude Latitude, la visualisation par défaut sera Longitude Latitude et il faudra cliquer à nouveau sur la visualisation où vous étiez pour constater les changements

## Features
Features implantées:
- Histogramme du traffic intéractif & réactif
- ScatterPlot Lat/Long & Long/Alt intéractifs et réactifs
- Zoom centré souris
- Double clic centré pour zoom
- Pan & Zoom
- Slider pour ajuster la transparence
- Slider pour ajuster les ID des trajectoires que l'on souhaite afficher
- Slider pour ajuster le temps des trajectoires que l'on souhaite afficher
- Slider pour ajuster l'altitude des trajectoires que l'on souhaite afficher
- Couleurs des segments selon leur altitude (voir fonction dédiée dans le code)
- Transition rapide entre les visualisations
- Sélection de trajectoire avec affichage des informations dans le coin sup droit
