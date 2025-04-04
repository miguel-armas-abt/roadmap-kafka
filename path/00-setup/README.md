# CONFIGURACIÓN

[← Regresar a notas](../../README.md) <br>

----

## ⚙️ Instalar Kafka

[Descargar](https://kafka.apache.org/downloads) `Binary downloads` en `.tgz` y guardar los binarios en la ruta sugerida `C:\dev-environment\kafka`.

> ### ▶️ Encender Zookeeper
> ```shell script
> bin\windows\zookeeper-server-start.bat config\zookeeper.properties
> ```
---

> ### ▶️ Encender Apache Kafka
> ```shell script
> bin\windows\kafka-server-start.bat config\server.properties
> ```
---