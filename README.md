# Proyecto_IA-II (Sistema de clasificación de hongos)

![Banner](https://github.com/IvanLeonardoNino/Proyecto_IA-II/assets/82769220/18aa1ae2-09fb-4cd7-aec7-35d9f455576c)

### Integrantes 
* Ivan Leonardo Niño Villamil - 2191968
* Juan David Morantes Vergara
* Mariana Robayo Nieto - 2195092

El proyecto de Inteligencia Artificial (IA) tiene como objetivo desarrollar un sistema de clasificación de hongos utilizando redes neuronales convolucionales (CNN). El desafío principal es entrenar un modelo capaz de identificar con precisión las 100 especies de hongos del conjunto de datos "Mushroom species", disponible en Kaggle.

Dataste y descripción:

Nombre:Mushroom species

Link: https://www.kaggle.com/datasets/thehir0/mushroom-species/

Peso:10 GB

Contenido:

En dataset cuenta con 77.382 fotos de 100 especies distintas de hongos tomadas en el territorio ruso, el dataset cuenta con una carpeta por cada especie de hongo y cada imagen es tomada de un hongo diferente y en diferentes ángulos por lo que no existen dos fotos iguales.

Se abordarán desafíos como la variabilidad en el tamaño, el formato y el color de las imágenes, así como la distinción entre especies similares. El objetivo es crear un clasificador preciso que, dada una imagen de un hongo, pueda identificar la especie con alta exactitud.

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


Se espera que este proyecto no solo logre clasificar con éxito estas especies, sino también se plantea como una herramienta útil en la identificación de hongos en entornos naturales o en estudios de biodiversidad, contribuyendo así a la ciencia y la preservación del medio ambiente.







