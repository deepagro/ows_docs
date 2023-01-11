# Servicio de notificaciones

*Notifications Service* se encarga de enviar notificaciones tanto de forma interna (aquellas que quedan serializadas en la base de datos del mencionado servicio) como de forma externa: vía SMS o e-mail (mediante `notification@ostrichapi.com`). Una notificación puede representar, por ejemplo, *alertas* de dispositivos.

Toda notificación, además del `payload` de la misma, posee propiedades como la urgencia y la severidad, el estado (abierta o cerrada), a qué usuario se le asigna y cuándo expira, entre otras.

> Documentación disponible en: [https://ostrichapi.com/notifications/redoc](https://ostrichapi.com/notifications/redoc)

## Releases

### Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
