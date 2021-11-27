# AgroTech Platform

En mi Trabajo Final de Grado se ha planteado una plataforma que utiliza diferentes tecnologías
para el sector agrícola.

En este caso se plantea un escenario con diferentes sensores para recolertar información, actuadores (ventanas, calefactores,...)
para según los datos recibidos, realizar una accion u otra. Además estos datos son almacenados en una base de datos y procesados para
mostrarse en una interfaz realizada en Angular.

Las tecnologías utilizadas son las siguientes:
- ROS2 y MicroROS para la comunicación en la red. Este utiliza una capa de DDS para la comuncación. El código se encuentra [aqui](https://github.com/pparrilla/ROS2_TFG).
- Firebase y SQLite3 para el almacenamiento de los datos.
- FastAPI para la comunicación entre la base de datos y la interfaz.
- Angular para la interfaz final. El código está en este [repositorio](https://github.com/pparrilla/AgriCloud-IOT-Angular).
