# Servicio de anotaciones

*Annotations Service* es el encargado del tagging de imágenes dentro de nuestro propio datalake, además de la recuperación de imágenes con tags específicos. El tagging puede realizarse utilizando recursos humanos o mediante diferentes algoritmos (por lo general, modelos de machine learning).

Cabe destacar que, el mencionado servicio, tiene la capacidad de exportar búsquedas en formato `CSV`, plano, mediante la ejecución de consultas complejas utilizando el lenguaje de consultas (DSL) [especificado](https://opensearch.org/docs/latest/opensearch/query-dsl/index/) por OpenSearch. El dataset exportado es enviado por e-mail al usuario que ejecutó la consulta vía `notification@ostrichapi.com`.

> Documentación disponible en: [https://ostrichapi.com/annotations/redoc](https://ostrichapi.com/annotations/redoc)

## Releases

### Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
