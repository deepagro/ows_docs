OWS es una arquitectura *multi-tenant* implementada bajo el patrón de diseño de microservicos, los cuales se comunican internamente (IPC) vía eventos.

## Estado del arte

A continuación, se presenta — de forma acotada — un diagrama que representa el estado actual de diseño de la composición de servicios de OWS; montados en un *cloud provider*.

![Arquitectura OWS](./../img/arch/v1.png "Estado del arte de aquitectura OWS")

Como se puede notar, se implementó el patrón de diseño *database-per-service*.

Cada servicio expone una REST API las cuales se encuentran bajo el dominio `https://ostrichapi.com`.

### Tecnologías

Con respecto a tecnologías utilizadas, se pueden nombrar las que siguen:

- Python, para el desarrollo de servicios. En particular, [FastAPI](https://fastapi.tiangolo.com/).
- [Docker Compose](https://docs.docker.com/compose/) para el orquestrado de servicios.
- [Traefik](https://traefik.io/traefik/) como load balancer y gateway.
- [PostgreSQL](https://www.postgresql.org/) y [DynamoDB](https://aws.amazon.com/es/dynamodb/) para serialización de recursos lógicos.
- [S3](https://aws.amazon.com/s3/) para serialización de objetos, tales como imágenes y archivos temporales.
- [Redis](https://redis.io/docs/manual/pubsub/) como broker pub/sub para implementar IPC vía eventos.
- [OpenSearch](https://opensearch.org/) para el indexado de metadata de objetos y recuperación elástica de datos.
- [ZooKeeper](https://zookeeper.apache.org/) para centralizar la serialización de configuraciones globales de la arquitectura de servicios presentada.
