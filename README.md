## Descripció del projecte
Aquest projecte pretén mostrar un gràfic animat de la distribució de la població a Catalunya en funció de la latitud i la longitud entre els anys 2003 i 2021.

## Obtenció de les dades
Dades de població extretes de l'IDESCAT:
https://www.idescat.cat/pub/?id=aec&n=925&t=2021

Dades de geolocalització extretes del Portal de dades obertes de la Generalitat de Catalunya:
https://analisi.transparenciacatalunya.cat/Urbanisme-infraestructures/Municipis-Catalunya-Geo/9aju-tpwc/data

Mapa obtingut a OpenStreetMap:
https://www.openstreetmap.org/export#map=8/41.665/1.066

## Tractament de les dades
Les dades de població s'han hagut d'estandaritzar, ja que hi ha nombrosos municipis que al llarg dels anys han anat canviat de nom. Els gràfics de població generats estan normalitzats de forma que el màxim del sector amb més població (tant per longitud com per latitud) té un valor constant.

## Resultat
A la següent figura es pot veure el resultat del projecte:

![cat-population-map](https://user-images.githubusercontent.com/2729145/173206733-26feecdf-5258-4ec4-adb9-e9e64f7d6d55.gif)
