# TFG 
En aquest repositori es troben els arxius necessaris per executar el codi i obtenir els resultats explicats en el Treball de Final de Grau relacionat amb l'estudi de la pèrdua de l’equilibri i la coordinació motora amb el posturògraf.

**carregar_dades.ipynb** \
Fitxer on s'han processat les dades dels 420 pacients i es troben creats els nous fitxers de tipus csv necessaris per a l'execució del codi principal. En aquest fitxer també es troben explicat cadascun dels fitxers creats i les variables que inclouen per poder realitzar els càlculs pertinents. D'aquest Jupyter notebook obtenim els següents arxius tipus .csv: \
    - Regressio_ROA.csv \
    - Regressio_ROC.csv \
    - Regressio_RGA.csv \
    - Regressio_RGC.csv \
    - VAL_ROA.csv \
    - VAL_ROC.csv \
    - VAL_RGA.csv \
    - VAL_RGC.csv \
    - indices.csv 

**codi_main.ipynb** \
Fitxer on es troben tots els càlculs i models entrenats que estan descrits a la memòria del TFG.

**Dades** \
Carpeta que inclou els nou fitxers creats i explicats en el Notebook carregar_dades.ipynb. Per executar el codi_main.ipynb s'han de descarregar els arxius tipus csv que inclou aquesta carpeta individualment i guardar-los en la mateixa carpeta que el codi.

**llibreries.txt** \
Fitxer de text que inclou els imports necessàries per poder executar el codi de carregar_dades.ipynb i codi_main.ipynb.
