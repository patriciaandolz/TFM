# Treball final del màster de _Data Science_

#  Descripció
Aquest projecte es correspon al desenvolupament del producte final del TFM _**Anàlisi SIG de l’evolució, seguretat i millora ambiental de la infraestructura ciclable de Barcelona**_. Aquest treball es basa en analitzar de forma estadística i geoespacial les dades obertes referents a la infraestructura ciclable de la ciutat de Barcelona, els aforaments de les vies, els sinistres associats a aquest mitjà de transport i els agents contaminants. Superposant tota aquesta informació es permet entendre les actuacions de l’Ajuntament per impulsar aquesta iniciativa sostenible.

En concret, la captura, el tractament i l'anàlisi estadística de les dades s'ha realitzat en ***[R](https://patriciaandolz.github.io/tfm/)***, mentre que l'anàlisi geoespacial s'ha dut a terme a ***ArcGIS Pro***. Finalment, s'ha publicat un [visor interactiu](https://patriciaandolz.maps.arcgis.com/apps/MapSeries/index.html?appid=d3808fb4190b40939b9d3bfea61f7f7b) amb les quatre temàtiques d'estudi i un espai per explorar les capes superposades a ***ArcGIS Online***, construit amb ***Web AppBuilder*** i ***Story Map Series***.

# Autors
* **Patricia Andolz Santacana**.

# Fitxers resultants
En aquest GitHub es poden trobar els següents fitxers:
*  **codi/codi_R_TFM_analisi_ciclable_BCN.Rmd** conté la implementació en R que carrega les dades de l'estudi i genera les capes a ArcGIS Pro utilitzant el conector R-ArcGIS Bridge, així com els elements per enriquir el visor d'AGOL
*  **codi/Dades** directori que conté els fitxers originals. En concret:
  *  **codi/Dades/accidents** directori que conté els conjunts CSV per l'estudi d'accidentalitat
  *  **codi/Dades/infraestructura_ciclable** directori que conté els conjunts ZIP per l'estudi de la infraestructura ciclable
  *  **codi/Dades/qualitat_aire** directori que conté el conjunt CSV per l'estudi de la qualitat de l'aire
  *  **codi/Dades/BCN_UNITATS_ADM** directori que conté els ZIP amb les dades administratives de Barcelona (municipi, districtes i barris)
  *  **codi/Dades/graf_viari** directori que conté els ZIP amb l'entramat de la xarxa vial
