En la actualidad, DeepAgro posee un repositorio de mas de 2 millones de imágenes súmamente detalladas de campos en diversos puntos geográficos — por lo general, en latinoamérica. Para la recopilación de las mencionadas imágenes, es entonces que DeepAgro posee un componente de captura denominado *Explorer*.

## Breve introducción

Explorer es un dispositivo AgTech de recuperación de información. Son dispositivos de bajo costo que contiene las siguientes características:

- Cámara HD.
- Módulo GPS.
- Disco duro extraíble y de capacidad aleatoria, dependiendo del cliente o tareas.
- *Explorer OS*: software implementado para la toma (y recuperación de metadata como coordenadas geográficas, temperatura y velocidad) de una imagen (encriptada) cada ~ 2 segundos.

![Dispositivo](./../img/explorer/device.png "Dispositivo"){ height=5; style="display: block; margin: 0 auto" }

Todo dispositivo se coloca en ciertas maquinarias agrícolas que tengan la capacidad de recorrer un lote. Por esto mismo, decimos que Explorer es un dispositivo *plug-and-play*. Por lo general, se colocan en los brazos de pulverizadoras — como se muestra a continuación.

![Dispositivo colocado 2](./../img/explorer/plugged-2.jpeg "Dispositivo colocado 2"){ width=400; style="display: block; margin: 0 auto" }

Explorer es un **ojo inteligente en el campo**. Captura imágenes HD a una altura aproximada de 1.5 metros (en el caso común de instalación en pulverizadoras). 

Las imágenes tomadas, junto con toda otra metadata específica, son luegos utilizadas con diferentes propósitos: entrenamiento de diversos sistemas de soporte a la decisión agrícola (por lo general, modelos de computer vision) para su utilización en SprAI como también vía servicios web (el anteriormente mencionado Predictions Service), construcción de mapas para la generación de reportes de estadísticas visuales, e inteligencia de negocios.

> Trivialmente, las imágenes capturadas por dispositivos Explorer son de mayor definición y exactitud que aquellas tomadas por satélites. Además, el **costo de recolección** de datos es **```0```**; comparando con ciertos planes de negocio que incluye, por ejemplo, volar drones por el lote

Debajo se observan caputuras ejemplos de un dispositivo Explorer.

![Samples](./../img/explorer/samples.png "Samples"){ height=5; style="display: block; margin: 0 auto" }

## Instalaciones

Actualmente, se encuentran instalados en diversas ubicaciones geográficas.

![Mapa explorer](./../img/explorer/map.png "Mapa explorer"){ height=5; style="display: block; margin: 0 auto" }

Explorer es comercializado por DeepAgro o brindado comodato para el posterior entrenamiento de modelos de computer vision específicos del cliente.
