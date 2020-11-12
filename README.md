# SEGUNDO_EXAMEN


## Instrucciones 
## Las respuestas de los ejercicios deberán entregarse en un documento en formato PDF y con capturas de pantalla
##  A partir de la siguiente secuencias Paired-End conteste las siguientes preguntas 

    1. Hacer un proceso de visualización de calidad con FastQC con las dos secuencias, utilizando algunas de las herramientas utilizadas
    FASTQC, GALAXY, PRINTSEQ. 
    a) ¿Cuántas secuencias tiene cada lectura?
    b) ¿Cuál es el porcentaje de GC predicho de acuerdo al análisis de FastQC?
    c) Explica como es la calidad de la lecturas y que regiones son necesarias quitar para realizar el trimming 
    
    2. Realiza el trimming de las secuencias con los siguientes parametros de Q30, HEADCROP:20, MINLEN:75 usando Trimmomatic
    También puedes usar Trimgalore en Galaxy. 
    
    3. Realiza la visulización de la calidad de la secuencias despues del recorte las seucencias nuevamente de FASTQC
    explica como cambiaron las lecturas. ¿Cuántas lecturas quedaron después del trimming?
    
    4. Realiza el ensamble de las secuencias utilizando Velvet en Galaxy o SPADES en Patric 
    
    5. Realiza la anotación de los archivos usando Prokka en Galaxy con 200 Minimum contig size (--mincontiglen), la otra herramienta
    que se puede utilizar es RAST, también pueden utilizar la herramienta PATRIC para la anotación que tiene RAST.
    
    6. Utilizando QUAST 
    ¿Cuál  es el valor del N50?
    ¿Cuál es el contig más pequeño?
    ¿Cuál es el tamaño del genoma?
    
    7. Utilizando OneCodex, GenomePeek o MIGA indica a que organismo pertenece 
    
 ## A partir del alienamiento múltiple realiza el arbol filogenético usando MEGA. 
    1. ¿Cuál es mejor modelo evolutivo?
    2. Utiliza 100 replicas de boostrap para un arbol por NJ y uno por MaximaVerosimilitud. 
    3. Visualizar el arbol utilizando ITOL 



                
