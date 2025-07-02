# taxon_name
Revisa el nombre cientifico aceptado comparandolo con World Flora (https://www.worldfloraonline.org/)

El programa trata de estandarizar metodologías para las evaluaciones de riesgo de especies exóticas invasoras en México. Las primeras aproximaciones para una evaluación de riesgo es la correcta identificación taxonómica. En este caso en particular es particular para plantas aunque no dudo que teniendo otra base de datos simialr se pueda expander a otros taxones.

La idea principal es que toma un nombre científico y lo valida con la base de datos. Utiliza el paquete WorldFlora en R. El equivalente anterior que está en desuso (ya no se actualiza en CRAN) es Taxostand. hhhh

El primer paso es bajar el balckbone mas reciente que es la base de datos con el contenido de todas las especies. Esose obtiene de la pagina de World Flora Online y en Downloads hay un archivo comprimido. Ese archivo se pone en el direcotriio en donde vas a trabajar o si no está allí en los comandos dentro del paquete WorfldFlora debe de especificar en donde se encuentra ese archivo.


