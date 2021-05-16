# Treball final del màster de _Data Science_

#  Descripció
Aquest projecte es correspon al desenvolupament del producte final del TFM _**Anàlisi SIG de l’evolució, seguretat i millora ambiental de la infraestructura ciclable de Barcelona**_. Aquest treball es basa en analitzar de forma estadística i geoespacial les dades obertes referents a la infraestructura ciclable de la ciutat de Barcelona, els aforaments de les vies, els sinistres associats a aquest mitjà de transport i els agents contaminants. Superposant tota aquesta informació es permet entendre les actuacions de l’Ajuntament per impulsar aquesta iniciativa sostenible.

En concret, la captura, el tractament i l'anàlisi estadística de les dades s'ha realitzat en ***[R](https://patriciaandolz.github.io/tfm/)***, mentre que l'anàlisi geoespacial s'ha dut a terme a ***ArcGIS Pro***. Finalment, s'ha publicat un [visor interactiu](https://patriciaandolz.maps.arcgis.com/apps/MapSeries/index.html?appid=d3808fb4190b40939b9d3bfea61f7f7b) amb les quatre temàtiques d'estudi i un espai per explorar les capes superposades a ***ArcGIS Online***, construit amb ***Web AppBuilder*** i ***Story Map Series***.

# Autors
* **Patricia Andolz Santacana**.

# Fitxers resultants
En aquest GitLab es poden trobar els següents fitxers:
*  **codi/scraper-ev-database.py** conté la implementació en Python del rastrejador que s'endinsa en la base de dades online ev-database i que acaba generant el conjunt de dades resultant
*  **codi/csv/ElectricVehicleCatalog.csv** conté en format de CSV les dades capturades durant el procés de scraping
*  **codi/csv/images** directori que conté en format JPG les imatges dels vehicles descarregats 
*  **AndolzSantacana_Patricia_Practica1_TCVD.pdf** conté l'informe detallat de la pràctica
