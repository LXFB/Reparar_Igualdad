Reparar_Igualdad
=================

Reparar_Igualdad es una modificación de la distribución Ubuntu GNU/Linux en su versión minimal-remix, creada con el único fin de dar una opcion unificada de herramientas básicas para reparar el sistema a los usuarios de netbooks del plan gubernamental Argentino Conectar_Igualdad. **No es oficial, ni guarda relación alguna con el plan Conectar_Igualdad**. 

Para utilizàr Reparar_Igualdad es necesario crear un USB de arranque y luego iniciar desde el mismo.

##Crear USB de arranque

###Windows

- Obtener [reparar_igualdad](http://sourceforge.com)
- Insertar la unidad USB
- Instalar LiveUSBCreator (ejecutar LiveUSBCreator.exe incluido en la carpeta descargada)
- Seguir las instrucciones de la imagen

###Linux

- Obtener [reparar_igualdad](http://sourceforge.com)
- En un terminal `sudo dd if=/ruta/a/repararIgualdad.ISO  of=/unidad_usb` **[ELIMINARA TODO EN EL USB]**
- **Ejemplo** `sudo dd if=/home/miusuario/Descargas/reparar_igualdad/Ubuntu-12.10.ISO  of=/dev/sdc1`
  
Para ver la ubicaciòn de la unidad USB `sudo cfdisk -l` para desmontarla `sudo umount unidad_usb`

##Iniciar desde el USB

Para arrancar desde la unidad USB es necesario configurar el BIOS. La interfaz del BIOS es distinta entre los dos modelos de netbooks entregadas. Se incluyen imàgenes de ambos modelos, llamando '**primera generacion**' a las netbook n2ww3 entregadas inicialmente y '**segunda generacion**' a las netbooks w23erw, seguir el instructivo que corresponda.

- Insertar la unidad USB en la màquina a reparar
- Iniciar la màquina
- Presionar **F2** de forma constante hasta ingresar al BIOS
- Seguir las instrucciones de las imagenes


Una vez iniciado se abrira un documento con ayuda. 

**ESTE SOFTWARE SE ENTREGA CON EL FIN DE QUE SEA UTIL -SIN GARANTIA ALGUNA- EL CORRECTO USO ES RESPONSABLIDAD DEL USUARIO**    
