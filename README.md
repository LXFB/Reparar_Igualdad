Reparar_Igualdad
=================

Reparar_Igualdad es una modificación de la distribución Ubuntu GNU/Linux en su versión minimal-remix, creada con el único fin de dar una opcion unificada de herramientas básicas para reparar el sistema a los usuarios de netbooks del plan gubernamental Argentino Conectar_Igualdad. 

**No es oficial, ni guarda relación alguna con el plan Conectar_Igualdad.** 

Para utilizàr Reparar_Igualdad es necesario crear un USB de arranque y luego iniciar desde el mismo.

##Crear USB de arranque

- Es necesario una unidad USB con capacidad de 2Gb o superior.

###Windows

- Obtener [reparar_igualdad](http://sourceforge.com)
- Insertar la unidad USB
- Ejecutar LiveUSBCreator.exe (incluido en la carpeta descargada)
- Seguir las instrucciones de la imagen

![Alt](http://fotos.subefotos.com/5b752e5f09845db5396653239109bb92o.png)

El contenido de la unidad USB **SERA BORRADO DE FORMA PERMANENTE** :exclamation:

###Linux

- Obtener [reparar_igualdad](http://sourceforge.com)
- En un terminal
- `sudo fdisk -l` # ver el punto de montaje de la unidad USB
- `sudo umount /dev/sdXY` # desmontar  [reemplazar **XY** con letra y numero correspondiente]
- `sudo dd if=/ruta/a/repararIgualdad.iso  of=/unidadUSB` # crear la unidad USB arrancable
- **Ejemplo** `sudo dd if=/home/miusuario/Descargas/reparar_igualdad/Ubuntu-i386-12.04.iso of=/dev/sdb`

El contenido de la unidad USB **SERA BORRADO DE FORMA PERMANENTE** :exclamation:

##Iniciar desde la unidad USB

Para arrancar desde la unidad USB es necesario configurar el BIOS. Existen dos interfaces de BIOS distintas en las netbooks del plan Conectar_Igualdad, segun el modelo de màquina. Se incluyen imàgenes para ambas interfaces, seguir la que corresponda.

- Insertar la unidad USB en la màquina a reparar
- Iniciar la màquina
- Presionar **F2** de forma constante hasta ingresar al BIOS
- Seguir las instrucciones de las imagenes 

###BIOS A
![Alt](http://fotos.subefotos.com/d38264e83658e9aabd79f313c07bac8bo.png)
![Alt](http://fotos.subefotos.com/a58649e564a5233266e6eb66b41d605fo.png)

###BIOS B
![Alt](http://fotos.subefotos.com/d93ae1ef4c2654614003d8f7a037ad5fo.png)

Una vez iniciado Reparar_Igualdad se mostrarà un documento con ayuda. 

**ESTE SOFTWARE SE ENTREGA SIN GARANTIA ALGUNA EL CORRECTO USO ES RESPONSABILIDAD DEL USUARIO**    
