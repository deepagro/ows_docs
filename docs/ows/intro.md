OWS es un conjunto de servicios web, implementados bajo las especificaciones REST, en la cual cada uno de estos cumple con responsabilidades específicas. 

Desde el inicio, OWS fue desarrollado para utilizarse de forma interna por el equipo de **Datos & Inteligencia Artificial** para, principalmente, **agilizar y mejorar los procedimientos** de entrenamiento de modelos de visión por computadora — los cuales, luego, son utilizados tanto comercial como internamente. Para lo anterior se necesitaba, en particular, especificar e implementar diferentes módulos encargados de:

1. Añadir y recuperar metadata específica de imágenes tomadas en diferentes lotes en Argentina, Brasil, EEUU y Uruguay;
2. construir una estructura de *datalake* en la cual se serialicen las anteriormente mencionadas imágenes, e
3. implementar sistemas de recuperación de información los cuales, utilizando el mencionado datalake como *fuente de verdad*, puedan ejecutar consultas complejas.

De esta forma, y con las más de **2 millones** de imágenes en alta definición — a no mas de 1.5 metros de altura del suelo — que posee DeepAgro, se realiza inteligencia de negocio (BI) y se entrenan sistemas inteligentes de soporte a la decisión específicos. Estos son utilizados, por ejemplo, en tiempo real en el producto de aplicación selectiva de herbicidas DeepAgro SprAI.

DeepAgro, con la ayuda de OWS, posee uno de los repositorios de imágenes de campos, en alta resolución, **más voluminoso y detallado del mercado latinoamericano**.
