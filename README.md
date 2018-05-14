# imagen4

Esta Imagen contiene las siguientes características:
Sistema operativo:
• Linux 0e19890c8964 4.9.93 x86_64 x86_64 x86_64 GNU/Linux
Componentes adicionales para su operación:
• Java sdk
    o jdk1.8.0_131
    o jdk1.7.0_71
• Hadoop 2.7.0
• apache-hive-1.2.1-bin
• sqoop-1.4.7.
• pig-0.15.0
• hbase-1.3.2
• anaconda3
• apache-flume-1.8.0-bin
• Python 3.6.3
• Jupiter
• Spark 2.0.0

Para realizar la generación de la imagen via dockerfile hacer los siguientes pasos:

Ir a la dirección https://github.com/rdiazr1/imagen4 descargar los archivos del url antes mencionado y colocarlos todos en una sola carpeta.

1) Ejecutar la siguiente instrucción para crear la imagen:
docker build -t imagen4 "path de archivo donde gardaste fichero Dockerfile”

una vez descargada la imagen ejecutar las siguiente instrucción.

2) para construcción del contenedor ejecutar la siguiente instrucción
docker run -it -v /host/data/path:/opt/data imagen4 /etc/bootstrap.sh -bash
