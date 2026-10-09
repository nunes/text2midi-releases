# Text2MIDI releases

Instaladores y actualizaciones de Text2MIDI para Windows x64. El código fuente se mantiene en un repositorio privado; este repositorio distribuye únicamente los paquetes y sus metadatos.

Descarga el archivo `Text2MIDI-<versión>-setup.exe` de la [última release](https://github.com/nunes/text2midi-releases/releases/latest). El instalador incluye Electron y el runtime de .NET del helper MIDI. Requiere Windows 11 con Windows MIDI Services para crear el puerto virtual; también permite elegir otras salidas MIDI disponibles.

La aplicación muestra su versión en la cabecera y conserva tamaño y maximización de la ventana. Busca nuevas releases al arrancar y cada cuatro horas. Cuando avisa de una actualización puedes aplazarla o aceptar: descarga y verifica el paquete y reinicia con instalación silenciosa, conservando la carpeta, los accesos directos, los ajustes y el proyecto local. El botón Actualizar permite buscar manualmente.

El instalador no está firmado con un certificado de distribución. El sonido procede del instrumento MIDI del DAW; Text2MIDI genera y reproduce las notas.

Cada release contiene el instalador, su `.blockmap` y `latest.yml`. Estos dos últimos archivos permiten las actualizaciones de la aplicación; para instalar basta el `.exe`.
