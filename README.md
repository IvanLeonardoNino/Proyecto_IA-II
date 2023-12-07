# Clasificación-de-Hongos

![Banner](https://github.com/IvanLeonardoNino/Proyecto_IA-II/assets/82769220/18aa1ae2-09fb-4cd7-aec7-35d9f455576c)


### Integrantes 
* Ivan Leonardo Niño Villamil - 2191968
* Juan David Morantes Vergara - 2191931
* Mariana Robayo Nieto - 2195092

El propósito fundamental de este proyecto es implementar y entrenar una red neuronal convolucional (CNN) con el fin de realizar predicciones precisas sobre las 16 familias de hongos que han sido identificadas manualmente por nuestro equipo de trabajo. Cada especie de hongos ha sido clasificada en una de estas 16 familias, y aquellas que no pudieron asignarse a una familia específica fueron eliminadas del conjunto de datos. La base de datos utilizada fue extraída de 'Mushroom species' en Kaggle, la cual consiste en carpetas de imágenes organizadas por especie de hongos.

Durante el procesamiento de las imágenes, nos aseguramos de que cada familia estuviera representada por un máximo de 1000 imágenes, garantizando así un equilibrio en la distribución de datos. El enfoque del modelo se centra en analizar de manera eficiente las características distintivas de cada familia de hongos, optimizando así la capacidad de predicción del sistema.

El objetivo final de este proyecto es desarrollar un modelo de predicción robusto que permita la clasificación precisa de hongos. Este enfoque no solo contribuirá a una identificación fiable de especies, sino que también facilitará la investigación y clasificación de estos organismos en nuestro entorno.
Diapositivas:
https://www.canva.com/design/DAF2Pdex28E/q514iYRIh1wsAJhmC-GnWg/watch?utm_content=DAF2Pdex28E&utm_campaign=designshare&utm_medium=link&utm_source=editor
Dataset Original y descripción:

Nombre:Mushroom species

Link: https://www.kaggle.com/datasets/thehir0/mushroom-species/

Peso:10 GB

Contenido:

En dataset cuenta con 77.382 fotos de 100 especies distintas de hongos tomadas en el territorio ruso, el dataset cuenta con una carpeta por cada especie de hongo y cada imagen es tomada de un hongo diferente y en diferentes ángulos por lo que no existen dos fotos iguales.

El repositorio ya incluye el conjunto de datos con la cantidad de imagenes que contiene cada una de las 100 especies de hongos:

* Amanita citrina: 292
* Amanita muscaria: 4258
* Amanita pantherina: 342
* Amanita rubescens: 532
* Apioperdon pyriforme: 1016
* Armillaria borealis: 270
* Artomyces pyxidatus: 923
* Bjerkandera adusta: 465
* Boletus edulis: 1469
* Boletus reticulatus: 253
* Calocera viscosa: 424
* Calycina citrina: 599
* Cantharellus cibarius: 846
* Cerioporus squamosus: 1523
* Cetraria islandica: 432
* Chlorociboria aeruginascens: 342
* Chondrostereum purpureum: 326
* Cladonia fimbriata: 312
* Cladonia rangiferina: 251
* Cladonia stellaris: 361
* Clitocybe nebularis: 456
* Coltricia perennis: 249
* Coprinellus disseminatus: 455
* Coprinellus micaceus: 417
* Coprinopsis atramentaria: 284
* Coprinus comatus: 1309
* Crucibulum laeve: 303
* Daedaleopsis confragosa: 536
* Daedaleopsis tricolor: 276
* Evernia mesomorpha: 709
* Evernia prunastri: 1465
* Flammulina velutipes: 694
* Fomes fomentarius: 5254
* Fomitopsis betulina: 1590
* Fomitopsis pinicola: 5096
* Ganoderma applanatum: 929
* Graphis scripta: 339
* Gyromitra esculenta: 482
* Gyromitra gigas: 1455
* Gyromitra infula: 312
* Hericium coralloides: 622
* Hygrophoropsis aurantiaca: 259
* Hypholoma fasciculare: 257
* Hypholoma lateritium: 371
* Hypogymnia physodes: 2166
* Imleria badia: 294
* Inonotus obliquus: 934
* Kuehneromyces mutabilis: 662
* Lactarius deliciosus: 278
* Lactarius torminosus: 344
* Lactarius turpis: 267
* Laetiporus sulphureus: 2302
* Leccinum albostipitatum: 465
* Leccinum aurantiacum: 553
* Leccinum scabrum: 1697
* Leccinum versipelle: 430
* Lepista nuda: 287
* Lobaria pulmonaria: 621
* Lycoperdon perlatum: 1117
* Macrolepiota procera: 901
* Merulius tremellosus: 392
* Mutinus ravenelii: 274
* Nectria cinnabarina: 320
* Panellus stipticus: 251
* Parmelia sulcata: 2654
* Paxillus involutus: 862
* Peltigera aphthosa: 278
* Peltigera praetextata: 291
* Phaeophyscia orbicularis: 246
* Phallus impudicus: 369
* Phellinus igniarius: 335
* Phellinus tremulae: 326
* Phlebia radiata: 287
* Pholiota aurivella: 407
* Pholiota squarrosa: 340
* Physcia adscendens: 369
* Platismatia glauca: 401
* Pleurotus ostreatus: 519
* Pleurotus pulmonarius: 329
* Pseudevernia furfuracea: 446
* Rhytisma acerinum: 803
* Sarcomyxa serotina: 246
* Sarcoscypha austriaca: 391
* Sarcosoma globosum: 281
* Schizophyllum commune: 1085
* Stereum hirsutum: 305
* Stropharia aeruginosa: 336
* Suillus granulatus: 458
* Suillus grevillei: 245
* Suillus luteus: 373
* Trametes hirsuta: 280
* Trametes ochracea: 266
* Trametes versicolor: 676
* Tremella mesenterica: 571
* Trichaptum biforme: 652
* Tricholomopsis rutilans: 256
* Urnula craterium: 300
* Verpa bohemica: 787
* Vulpicida pinastri: 865
* Xanthoria parietina: 5837

Al momento de Procesar y clasificar los datos anteriores en Familias obtuvimos las siguientes:

* Familia Amanita
* Familia Boletus
* Familia Cladonia
* Familia Coprinellus
* Familia Daedaleopsis
* Familia Ervenia
* Familia Formitopsis
* Familia Gyromitra
* Familia Hypoloma
* Familia Lactarius
* Familia Leccinum
* Familia Peltigera
* Familia Phellinus
* Familia Pholiota
* Familia Suillus
* Familia Trametes

Se espera que el proyecto culmine con un modelo de inteligencia artificial efectivo y útil para la identificación de especies de hongos, contribuyendo al avance en la investigación y conocimiento de la micología.




