# Choribot

## Introducción

Bot pensado para ser usado comunidades de Discord. 

## Versiones

> ### Alpha 0.0.3 - 13/09/2017
	- Creación del bot, utilizando discord.js.
	- Integración del comando $Ping, $Ayuda, $About, $Reacciones, $Presentacion, $Decir.
	- Reacciones a algunas frases (Actualmente escasas). Se pueden ver con $Reacciones.
	
> ### Alpha 0.0.4
	- Separación de los comandos en archivos propios.
	- Se ha añadido el comando $Dado (num)d(num).
	
> ### Alpha 0.0.5
	- Se ha añadido el comando $Sugerencia.
	- Se han añadido los comandos $Canta y $Callate para conectar el bot al canal de voz y que cante/deje de cantar.
	
> ### Alpha 0.0.6
	- Se han modificado los comandos $Canta y $Callate, ahora es un solo comando $Musica que de momento reproduce una canción, en futuras actualizaciones reproducirá una canción aleatoria de una carpeta.
	- Se ha comenzado a implementar el comando $Busca, que tendrá como finalidad reproducir el audio de un video de Youtube. De momento solo reproduce el audio de un video.

> ### Alpha 0.0.7
	- Se ha finalizado el comando $Musica, ahora te permite poner, quitar o cambiar de canción de forma aleatoria de la carpeta de música que se encuentra en la raíz del proyecto.
	- Ahora el bot te da la bienvenida cuando entras al canal de voz principal.

> ### Alpha 0.0.7
	- Se ha incluido el comando $Musica buscar que permite buscar una canción específica de la carpeta música.
	- Se ha incluido el comando $Musica lista que te envía por privado la lista de canciones disponibles.
	- Se han añadido en la raíz del proyecto unos ejecutables para lanzar el bot sin necesidad de entrar en la consola.
	- Mejora del comando $Ayuda para evitar flood de mensajes.
	- Mejora del comando $Reacciones.
	- Se ha incluido el comando $Verid para el administrador que permite ver el id de un canal.

> ### Beta 0.1
	-Primera beta del bot, alcanzamos este estado porque creo que el bot ya tiene unas funcionalidades básicas suficientes para resultar de alguna utilidad.
	-Interconexión Discord-Telegram. Choribot ha decidió viajar al mundo de la multiplataforma, conectando mensajes de un chat de Telegram con un canal de texto de Discord, en ambas direcciones. Código adaptado de TediCross (https://github.com/TediCross/TediCross)
	-Se ha integrado un WebHook en el canal de Discord (Esto no aparece en el código, pero se da como sugerencia para ver actualizaciones del bot).

>### Beta 0.2
	-Implementación del comando $Llamar nombre, que manda mensajes a un usuario por privado hasta que recibe el comando $Llamar Parar.

>### Beta 0.3
	-Solución de errores del comando $Llamar, ahora para el envío de mensajes cuando se ejecuta el comando $Llamar parar correctamente.
	-Ahora el bot tiene estado cuando arranca.
	-Se ha creado el fichero Inicio.js que se ejecuta cuando se inicia el bot, por si fuera necesario hacer más cosas en este momento.

>### Beta 0.4
	-Implementación del comando $E3 para ver información relativa al evento de este año.
	-Ahora el comando $Llamar funciona con menciones (@alguien).
	-El comando $Llamar ahora envía una imagen en lugar de texto.
	-Actualización de $Ayuda.

>### Beta 0.5
	-Solución de errores en $Llamar, ahora debe enviar alertas a los usuarios sin problemas.
	-Mejora del comando borrar, borra automáticamente el mensaje escrito con este comando.

>### Beta 0.6
	-Se ha cambiado el prefijo de $ a / para tener compatibilidad con Telegram y proceder a implementar algunos comandos en esta última plataforma.
	-Ahora los comandos de Discord pueden lanzarse desde Telegram respetando los permisos de Discord.
	-En Telegram aparecen los comandos al poner / en el chat grupal.
	-Se le ha puesto imagen al Bot en Telegram.
	-Ahora se ejecutan comandos de mensajes editados.
	-Solución de errores varios.

>### Beta 0.7
	-Eliminado el comando /E3, almacenado en una nueva carpeta para futuras reutilizaciones.
	-Ahora el Bot dice quien se conecta y se desconecta a un canal de voz dado, con mecanismo anti flood.

>### Beta 0.8
	-Añadido comando /conectados que indica aquellos miembros conectados a un canal de voz

>### Versión 1.0
	Tras un largo tiempo en desarrollo, por fin pasamos el bot a la versión 1.0. Considero que ya realiza suficientes acciones para ser considerado útil. Estos son los cambios que se han realizado:
	-Añadido al comando Música la opciones Youtube, que nos permite buscar una canción por su nombre en la plataforma y reproducir la primera encontrada.
	-Añadido también a su vez el comando Youtube, que hace lo mismo, pero nos permite un acceso más rápido.
	-Ahora tanto cuando buscamos una canción en la carpeta local como cuando la buscamos en Youtube se va a reproducir en bucle, de forma que parar pararla tendremos que hacer un /musica off o un /youtube off, ambos hacen también lo mismo.
	-Ayuda actualizada.

### Versión 1.1
	-Limpieza de paquetes para facilitar lanzamiento en Docker.

## Próximas implementaciones
	- Documentar la instalación del bot
	- Comando $Sorteo
