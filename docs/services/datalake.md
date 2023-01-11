# Servicio de datalake

*Datalake Service* es el servicio encargado buscar objetos — por lo general, imágenes, dentro de nuestra propia estructura de serialización de *big data*. Además, posee herramientas para obtener información resumida, o estadísticas, del estado actual del datalake.

El servicio permite exportar búsquedas, mediante la ejecución de consultas complejas escritas en el lenguaje de consultas ([DSL](https://opensearch.org/docs/latest/opensearch/query-dsl/index/)) de OpenSearch, en formato `CSV`. El archivo construido es enviado por e-mail al usuario que ejecutó la acción vía `notification@ostrichapi.com`. Se destaca que, dentro de DeepAgro, utilizamos los datasets exportados para agilizar el entrenamiento y testing de modelos de machine learning.

> Documentación disponible en: [https://ostrichapi.com/datalake/redoc](https://ostrichapi.com/datalake/redoc)

## Releases

### Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
