# Guía de uso
Este bot ha sido creado con el objetivo de facilitar y afianzar todo lo posible la retransmisión de contenido de formato de audio en canales de stage.
<br>
Dado su uso restringido y el deseo de evitar demasiado tráfico de acciones por parte de usuarios carentes de los permisos, hemos decidido evitar la creación de un archivo `/ayuda` y hacer así esta página desde la que se podrá comprobar la información de los diferentes comandos, botones y menús del bot.

<br><br>

| Nombre                     |        |
|:---------------------------|:-------|
| Actaulización de los comandos | [➡️](#actualización-de-los-comandos)
| Cancelación de eventos | [➡️](#cancelación-de-eventos) |
| Configuración de canales   | [➡️](#configuración-de-canales) |
| Eliminación de archivos de audio | [➡️](#eliminación-de-archivos-de-audio) |
| Modificación de archivos y eventos | [➡️](#modificación-de-archivos-y-eventos) |
| Prueba de conexión y velocidad | [➡️](#prueba-de-conexión-y-velocidad-ping) |
| Reporte de errores | [➡️](#reporte-de-errores) |
| Subida de archivos de audio | [➡️](#subida-de-archivos-de-audio) |

<br><br><br><br>

### Actualización de los comandos

### Cancelación de eventos

### Configuración de canales
Para realizar la configuración de canales, como el de stage o la [Biblioteca](#biblioteca) se hace uso del comando `/config` con la siguiente estructura:
```txt
/config stage <canal>
/config biblioteca <canal>
```
> NOTA: Si no sabe qué especificar en [&lt;canal&gt;](#ltcanalgt), aparecerá una breve descripción justo encima de la barra de texto cuándo lo esté introduciendo el campo.

### Creación de un evento

### Eliminación de archivos de audio

### Modificación de archivos y eventos

### Prueba de conexión y velocidad `/ping`

### Reporte de errores

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

#### Biblioteca
Canal de texto en el que se muestran los diferentes archivo de audio almacenados por el bot junto con los eventos creados. Desde este canal se puede realizar así la gestión de contenido por medio de los botones en los mensajes.