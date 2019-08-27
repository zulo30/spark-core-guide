# Spark-Core-Guide
Esta es una pequeña guía para empezar a divertirse con el micro controlador Spark Core hecho Particle

## Core Modes

### Conectado 
cuando el dispositivo esta respirando celeste (Ciano) significa conectado a internet.Cuando está en este modo, puede llamar a funciones y flashar su codigo.

### Flasheando 
tu dispositivo está cargando una app o actualizado su firmware. este modo se diparara con una actualización de firmware o por el código cargando al dispositivo.


### Buscando una conexion a internet 
tu dispositivo está tratando de encontrar internet. Si ya ingresó sus credenciales de wifi, dele a su dispositivo unos segundos para conectarse y comenzar a respirar cian. Si aún no ha conectado su dispositivo a wifi, configúrelo en modo de escucha. Si su Core parpadea continuamente en verde y no se detiene, intente realizar una actualización completa del firmware.


### Modo Escucha
cuando su dispositivo está en modo de escucha, está esperando que su entrada se conecte al wifi. Su dispositivo debe estar en modo de escucha para comenzar a conectarse con la aplicación móvil o por USB

para poner tu dispositivo en modo escucha presiona el boton `MODE` por 3's, hasta que la LED RGB empieze  


### Resetear wifi Network

Para borrar las redes wifi almacenadas en su dispositivo, mantenga presionado el botón `MODE` durante unos diez segundos, hasta que el LED RGB parpadee rápidamente en azul.

PROCEDIMIENTO: 

El procedimiento es el mismo que el descrito anteriormente (Modo DFU), pero en este caso debe continuar presionando el botón MODE hasta que vea que el dispositivo cambia de amarillo intermitente a blanco intermitente. Luego suelta el botón. El dispositivo debe comenzar después de que se complete el restablecimiento de fábrica.

1.  Mantenga presionados `AMBOS` botones.
2.  Suelte solo el botón `RST`, mientras mantiene presionado el botón `MODE`.
3.  Espere a que el LED comience a parpadear en amarillo (continúe presionando el botón`MODE`).
4.  El LED se iluminará en blanco fijo (continúe presionando el botón` MODE`).
5.  Finalmente, el LED se volverá blanco intermitente rápidamente.
6.  Suelte el botón MODE.



## Reseteado de Fabrica

Un restablecimiento de fábrica restaura el firmware del dispositivo a la aplicación Tinker predeterminada y borra todas sus credenciales de Wi-Fi.



## recursos

- core quickstart | [https://docs.particle.io/tutorials/device-os/led/core/](https://docs.particle.io/tutorials/device-os/led/core/) 
- webhooks | [https://docs.particle.io/tutorials/device-cloud/webhooks/](https://docs.particle.io/tutorials/device-cloud/webhooks/)
- datasheet | [https://docs.particle.io/](https://docs.particle.io/datasheets/discontinued/core-datasheet/)
- sitio viejo | [https//www.particle.io/?redirected=true](https://docs.particle.io/datasheets/discontinued/core-datasheet/)
- particle  | []()
- troubleshooting tools | [https://docs.particle.io/support](https://docs.particle.io/support/troubleshooting/troubleshooting-tools/core/#core-dfu-commands-)
