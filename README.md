# Teledeteccion
Introducción
Esta página proporciona una breve introducción al análisis de datos satelitales con R. Antes de leer esto, primero debe aprender los conceptos básicos del paquete de ráster .

Obtener imágenes de satélite para un proyecto específico sigue siendo uno de los pasos más desafiantes en el flujo de trabajo. Debe encontrar los datos más adecuados para su objetivo particular. Algunas propiedades importantes a considerar al buscar los datos de detección remota (satélite) incluyen:

Resolución espacial (tamaño de píxel) * referencia *
Resolución temporal (tiempo de retorno, disponibilidad de imágenes histróticas y para un momento particular en el tiempo) * referencia *
Resolución espectral (partes del espectro electromagnético (longitudes de onda) que se detectan, también conocidas como "bandas") * referencia *
Resolución radiométrica (sensibilidad, capacidad para medir pequeñas diferencias)
Calidad (por ejemplo, cobertura de nubes o artefactos en datos (lea sobre problemas en Landsat ETM + )
Existen numerosas fuentes de datos obtenidos por teledetección desde satélites. En general, los datos de resolución espacial muy alta están disponibles como productos comerciales (costosos). Los datos de resolución espacial más bajos están disponibles gratuitamente en la NASA, la ESA y otras misiones. En este tutorial usaremos los datos Landsat 8 , Landsat 7 , Landsat 5 , Sentinel y MODIS disponibles de forma gratuita. El programa Landsat es el programa satelital de observación de la Tierra más antiguo con una serie de satélites lanzados en las últimas cuatro décadas.

Puede acceder a estos datos desde varias fuentes, incluyendo:

http://earthexplorer.usgs.gov/
https://lpdaacsvc.cr.usgs.gov/appeears/
https://search.earthdata.nasa.gov/search
https://lpdaac.usgs.gov/data_access/data_pool
https://scihub.copernicus.eu/
https://aws.amazon.com/public-data-sets/landsat/
Este sitio web enumera 15 fuentes de datos de teledetección de libre acceso.

Es posible descargar algunos datos satelitales usando R-packages. Puede usar el paquete MODIS o MODISTools para buscar, descargar y preprocesar diferentes productos MODIS .
