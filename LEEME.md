# Google Drive Upload Tool
Una herramienta para subir archivos a Google Drive. El programa resume las subidas en caso de que ocurra una falla. Es perfecto para subir archivos grandes o si tu conexi�n es inestable. Adicionalmente, los archivos preservar�n su fecha de modificaci�n. Tambi�n, puedes navegar en tu Drive y subir archivos y carpetas a un lugar determinado.

# �C�mo usarlo?
1. Antes de usar este programa, siga el paso 1 de esta gu�a de Google: [https://developers.google.com/drive/v3/web/quickstart/dotnet](https://developers.google.com/drive/v3/web/quickstart/dotnet).
2. Luego, lanza el programa. Tendr�s que autorizar tu cuenta para poder usar el programa.
3. �Comienza a subir y descargar archivos!

# �C�mo subo un archivo o carpeta?
1. Simplemente, arrastre el archivo o carpeta al programa.
2. Presione el bot�n "Subir".

* Las carpetas subir�n con su estructura original.
* Si un archivo es interrumpido, usted podr� resumir la subida desde el punto en que la subida fue interumpida.

# �Como selecciono una carpeta?
* Simplemente, navega a la carpeta donde desee subir sus archivos.
* Para cambiar la carpeta a subir de un archivo que ya est� en la lista de subida, seleccione la carpeta en el navegador de carpetas y presione el bot�n "Subir archivo(s) a esta carpeta".

# �C�mo creo una carpeta?
1. Navegue al lugar donde desee crear la carpeta nueva.
2. Presione en "Crear Carpeta".
3. Escriba el nombre de la carpeta nueva y presione OK.

# �C�mo verifico si el ID de la carpeta est� correcta?
1. Escriba el ID de la carpeta en el blanco debajo del texto "Subir a este ID de directorio..."
2. PResione el bot�n titulado "Obtener Nombre de la Carpeta"
3. Si el ID es correcto, ver�s el nombre a la izquierda del bot�n. Si el ID es incorrecto, ver�s un mensaje de error notificando que el ID es incorrecto.

# �C�mo descargo un archivo?
1. Seleccione un archivo en la lista de archivos.
2. Presione el bot�n "Descargar" o alternativamente, presione ALT + D en su teclado.
3. Escoja una carpeta para descargar su archivo y presione en "Save".
4. La descarga comenzar�.

# �Puedo descargar m�s de un archivo?
�Absolutamente! Simplemente, seleccione los archivos y presione las teclas ALT + D en su teclado. Luego, seleccione una carpeta para descargar sus archivos.

# �Puedo descargar una carpeta y todo su contenido?
�Absolutamente! Simplemente, seleccione la carpeta y presione las teclas ALT + D en su teclado. Luego, seleccione una carpeta para descargar la carpeta y todo su contenido.

# �C�mo guardo el checksum de un archivo?
1. Seleccione el archivo.
2. Presione en "Guardar archivo MD5", Alternativamente, presione ALT + C en su teclado.
3. Busque un lugar para guardar el archivo.

# �C�mo guardo el checksum de m�s de un archivo?
1. Seleccione los archivo presionando la tecla Ctrl o Shift en su teclado, o presione ALT + A para seleccionar todos los archivos.
2. Presione el bot�n "Guardar Checksums de los archivos". Alternativamente, presione ALT + C en su teclado.
3. Busque un lugar para guardar el archivo.

# �C�mo guardo el checksum del contenido de una carpeta?
1. Seleccione la carpeta para guardar los checksums de su contenido.
2. Presione ALT + C en su teclado.
3. Busque un lugar para guardar el archivo. 

Los checksums utilizados son los que Google Drive genera y almacena.

# �C�mo env�o uno o m�s archivos o carpetas a la basura?
1. Seleccione el/los archivo(s) o carpeta(s) a enviar a la basura. 
2. Presione la tecla "Delete" en su teclado

# �C�mo restauro uno o m�s archivos o carpetas de la basura?
1. Presione el bot�n "Ver Basura"
1. Seleccione el/los archivo(s) o carpeta(s) a restaurar
2. Presione las teclas ALT + R en su teclado

# Shortcuts del teclado:
* **Enter**: Entrar en carpeta.
* **Delete**: Mover archivo o carpeta a la basura.
* **F5**: Refrescar la lista de archivos y carpetas.
* **ALT + A**: Seleccionar todos los archivos o carpetas.
* **ALT + C**: Guardar checksum de uno o m�s archivos o el contenido de una carpeta.
* **ALT + D**: Descargar uno o m�s archivos o el contenido de una carpeta.
* **ALT + R**: Cuando no est�s en la basura, renombrar un archivo o carpeta. Cuando est�s en la basura, restaura el archivo o carpeta.

# �Como abrir y compilar este proyecto?
Este proyecto fue escrito usando Visual Studio 2017, en el lenguaje Visual Basic .NET. Necesitar�s tener los componentes de Windows Desktop instalado para poder abrir y editar este proyecto. Tambi�n, necesitar�s las APIs de Google Drive los cuales est�n disponibles en el NuGet Package Manager.

�Disfruten!

# Historial de cambios:
Pueden ver el historial de cambios [presionando aqu�](https://github.com/moisesmcardona/GoogleDriveUploadTool/blob/master/Google%20Drive%20Uploader1/Changelog.txt).