# Treball final del màster de _Data Science_

#  Descripció
Aquest projecte es correspon al desenvolupament del producte final del TFM _**Anàlisi SIG de l’evolució, seguretat i millora ambiental de la infraestructura ciclable de Barcelona**_. Aquest treball es basa en analitzar de forma estadística i geoespacial les dades obertes referents a la infraestructura ciclable de la ciutat de Barcelona, els aforaments de les vies, els sinistres associats a aquest mitjà de transport i els agents contaminants. Superposant tota aquesta informació es permet entendre les actuacions de l’Ajuntament per impulsar aquesta iniciativa sostenible.

En concret, la captura, el tractament i l'anàlisi estadística de les dades s'ha realitzat en ***[R](https://patriciaandolz.github.io/tfm/)***, mentre que l'anàlisi geoespacial s'ha dut a terme a ***ArcGIS Pro***. Finalment, s'ha publicat un [visor interactiu](https://patriciaandolz.maps.arcgis.com/apps/MapSeries/index.html?appid=d3808fb4190b40939b9d3bfea61f7f7b) amb les quatre temàtiques d'estudi i un espai per explorar les capes superposades a ***ArcGIS Online*** (AGOL), construit amb ***Web AppBuilder*** i ***Story Map Series***.

# Autors
* Autora del TFM: **Patricia Andolz Santacana**
* Directora del TFM: **Anna Muñoz Bollas**
* Professor responsable de l'assignatura: **Albert Solé Ribalta**

# Estructura del Git
En aquest GitHub es poden trobar els següents fitxers:
*  **index.html** conté la [maquetació del codi d'R](https://patriciaandolz.github.io/tfm/)

*  **codi/codi_R_TFM_analisi_ciclable_BCN.Rmd** conté la implementació en R que carrega les dades de l'estudi i genera les capes a ArcGIS Pro utilitzant el conector R-ArcGIS Bridge, així com els elements per enriquir el visor d'AGOL

*  **codi/Dades** directori que conté els fitxers originals descarregats d'OpenData Barcelona i Catalunya. En concret:
     *  **codi/Dades/T1.infraestructura_ciclable** directori que conté els conjunts ZIP per l'estudi de la infraestructura ciclable
     *  **codi/Dades/T2.aforaments** directori que conté els conjunts CSV per l'estudi d'ús de la bicicleta
     *  **codi/Dades/T3.accidentalitat** directori que conté els conjunts CSV per l'estudi d'accidentalitat
     *  **codi/Dades/T4.qualitat_aire** directori que conté el conjunt CSV per l'estudi de la qualitat de l'aire
     *  **codi/Dades/BCN_UNITATS_ADM** directori que conté els ZIP amb les dades administratives de Barcelona (municipi, districtes i barris)
     *  **codi/Dades/graf_viari** directori que conté els ZIP amb l'entramat de la xarxa vial     


*  **codi/Exports** directori que conté les capes exportades d'ArcGIS Pro. En concret:
     *  **codi/Exports/T1.infraestructura_ciclable** directori que conté els _shapefiles_ de les capes de la infraestructura ciclable
     *  **codi/Exports/T2.aforaments** directori que conté els _shapefiles_ de les capes d'ús de la bicicleta
     *  **codi/Exports/T3.accidentalitat** directori que conté els _shapefiles_ de les capes d'accidentalitat
     *  **codi/Exports/T4.qualitat_aire** directori que conté els _shapefiles_ de les capes de la qualitat de l'aire


*  **codi/AGOL** directori que conté els recursos generats a R per enriquir el visor d'AGOL.
