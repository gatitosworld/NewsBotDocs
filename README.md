# Guía de uso
Este bot ha sido creado con el objetivo de facilitar y afianzar todo lo posible la retransmisión de contenido de formato de audio en canales de stage.
<br>
Dado su uso restringido y el deseo de evitar demasiado tráfico de acciones por parte de usuarios carentes de los permisos, hemos decidido evitar la creación de un archivo `/ayuda` y hacer así esta página desde la que se podrá comprobar la información de los diferentes comandos, botones y menús del bot.

<br><br>

| Nombre                                |                                            |
|:--------------------------------------|:-------------------------------------------|
| Actaulización de los comandos         | [➡️](#actualización-de-los-comandos)       |
| Cancelación de eventos                | [➡️](#cancelación-de-eventos)              |
| Configuración de canales              | [➡️](#configuración-de-canales)            |
| Eliminación de archivos de audio      | [➡️](#eliminación-de-archivos-de-audio)    |
| Modificación de archivos y eventos    | [➡️](#modificación-de-archivos-y-eventos)  |
| Prueba de conexión y velocidad        | [➡️](#prueba-de-conexión-y-velocidad-ping) |
| Reporte de errores                    | [➡️](#reporte-de-errores)                  |
| Subida de archivos de audio           | [➡️](#subida-de-archivos-de-audio)         |

<br><br><br><br>

### Actualización de los comandos
Para la actualización de los comandos slash será necesario el uso del comando `/actualizar`.
<br>
No se necesita ningún tipo de campo o opción extra, simplemente su uso es suficiente.

![imágen](media/comando%20actualizar.png)

<br><br>

### Cancelación de eventos
Para poder cancelar de forma óptima un evento se puede hacer *click* en el botón de cancelar que encontrarás bajo su mensaje embed, pero en el caso de que hayas borrado sin querer el mensaje, puedes hacerlo con ayuda del comando `/cancelar` que te mostrará una lista de los eventos programados y entre los que tendrás que escoger uno.

<br><br>

### Configuración de canales
Para realizar la configuración de canales, como el de stage o la [Biblioteca](#biblioteca) se hace uso del comando `/config` con la siguiente estructura:
```txt
/config stage <canal>
/config biblioteca <canal>
```
> NOTA: Si no sabe qué especificar en [&lt;canal&gt;](#canal-o-canal), aparecerá una breve descripción justo encima de la barra de texto cuándo lo esté introduciendo el campo.

<br><br>

### Creación de un evento
Haz uso del comando `/nuevo evento` y verás un nuevo formulario que tendrás que cubrir para crear el evento.

![imágen](media/Módulo%20nuevo%20evento.png)

Una vez terminado y enviado el formulario, se te solicitará que confirmes que los datos son correctos, en caso de no serlos, debe corregirlos. Si desea proceder, simplemente haga uso de su correspondiente botón "*PUBLICAR*"

<br><br>

### Eliminación de archivos de audio
Gracias al comando `/eliminar` podrás deshacerte de un archivo de la [Biblioteca](#biblioteca) pero necesitarás la [ID de archivo](#id-de-archivo).
```txt
/eliminar <id>
```
Para facilitar el trabajo, existe también un botón que cumple la misma función.
> NOTA: Si no sabe qué especificar en [&lt;id&gt;](#id-o-id), encontrará una breve descripción del valor que debe introducir justo encima de la barra de texto<br>
> Adelantando futuro trabajo, se trata de la [ID de archivo](#id-de-archivo).

<br><br>

### Modificación de archivos y eventos

<br><br>

### Prueba de conexión y velocidad `/ping`

<br><br>

### Reporte de errores

<br><br>

### Subida de archivos de audio


<br><br><br><br>

## Glosario

<br><br>

#### [archivo] o &lt;archivo&gt;
Campo de un comando slash en el que se debe adjuntar un archivo.<br>
Se pueden introducir múltiples formatos, pero tendrá que corresponderse con las necesidades del comando. 

<br><br>

#### [canal] o &lt;canal&gt;
Campo de un comando slash en el que se debe introducir el nombre de un canal de un determinado tipo (Algunos comandos requerirán un comando stage, otros de texto...)

<br><br>

#### [id] o &lt;id&gt;
Campo de un comando slash en el que se debe introducir una ID de archivo, error, evento... Lo que el comando solicite.

<br><br>

#### Biblioteca
Canal de texto en el que se muestran los diferentes archivo de audio almacenados por el bot junto con los eventos creados. Desde este canal se puede realizar así la gestión de contenido por medio de los botones en los mensajes.

<br><br>

#### ID de archivo
Se denomina "ID de archivo" al número único asignado a un archivo de audio.
<br>
Se podrá encontrar en el embed enviado tras la publicación del audio.