# 
![Catto](https://i.imgur.com/5Gr6rgP.png#only-light)
![Catto](https://i.imgur.com/B1K20BP.png#only-dark)

Catto es un bot de Discord que busca incentivar la participación de los usuarios en los canales de voz de los servidores de Discord. Para ello, Catto ofrece una serie de opciones que puedes utilizar para ello, a demás, de diferentes enfoques en moderación y más cosas por llegar.

## ¿Cómo funciona?

Para empezar, al agregar el bot a tu servidor, los módulos de experiencia tanto texto como voz se activan por defecto, por lo que no es necesario configurar nada para empezar a utilizarlo. Sin embargo, si deseas cambiar la configuración de los módulos, puedes hacerlo utilizando el comando `config` y el nombre del módulo que deseas configurar.

## Comandos
Ejemplo: `/admin disable` - En caso de que quieras desactivar el módulo de experiencia de texto o de voz, solo debes ejecutarlo y seleccionar el que desees desactivar. 

En todo caso, también tienes los comandos `/admin config xp` para que puedas seleccionar cuanta experiencia quieres que se otorgue a los usuarios, el comando te da la opción de establecer estos valores tanto para voz como para texto.

Por último tenemos el comando `/admin config xp-channel` que te permite seleccionar el canal en el que se mostrarán los mensajes de experiencia, por defecto al subir de nivel un usuario, el bot responde al mensaje con el que subió de nivel, pero si deseas que se muestre en un canal en específico, puedes hacerlo con este comando, también lo puedes utilizar para seleccionar el canal para los usuarios que suben de nivel en canales de voz.

### Comandos de Administrador

A continuación te dejo la lista completa de comandos que puedes utilizar como administrador:

* `/admin disable` - Puedes desactivar un módulo de el bot completamente.
* `/admin enable` - Puedes activar un módulo de el bot completamente.
* `/admin config notification` - Puedes personalizar el mensaje que se envía cuando un usuario sube a un nuevo nivel.
* `/admin config rol` - Selecciona los roles que quieres que se otorguen al subir de nivel.
* `/admin config xp` - Establece el mínimo y máximo de experiencia que se le dará a los usuarios.
* `/admin config xp-channel` - Selecciona el canal donde se enviarán la notificación al momento que un usuario sube de nivel.
* `/admin reset user` - Reinicia completamente la experiencia y niveles de un usuario.
* `/admin reset server` - Reinicia completamente la experiencia de todos los miembros del servidor.
* `/admin setup voices` - Crea la categoría y canal para que funcione como medio para crear los canales temporales de voz.

### Comandos temporales de voz

El bot cuenta con un módulo para crear canales temporales en base a un canal fijo que se usará para crear los demás canales.
Una vez que los usuarios crean su canal de voz al unirse al canal base, pueden usar los siguientes comandos para personalizar su canal:

* `/voice name` - Cambia el nombre de tu canal de voz.
* `/voice limit` - Cambia el límite de usuarios que pueden unirse a tu canal de voz.
* `/voice lock` - Bloquea tu canal de voz para que nadie más pueda unirse.
* `/voice unlock` - Desbloquea tu canal de voz para que otros usuarios puedan unirse.
* `/voice reject` - Expulsa a un usuario de tu canal de voz.
* `/voice permit` - Otorga acceso a un usuario a tu canal de voz.
* `/voice claim` - Reclama un canal de voz cuando su dueño original no se encuentre presente en el mismo.
* `/voice ghost` - Oculta el canal de voz a los miembros del servidor.
* `/voice unghost` - Muestra el canal de voz a los miembros del servidor.
* `/voice bitrate` - Establece el bitrate que desees a el canal de voz.
* `/voice invite` - Invita un usuario en especifico del servidor para unirse a tu canal de voz.
* `/voice transfer` - Transfiere la propiedad de tu canal de voz a otro usuario.
* `/voice reset` - Reestablece los permisos de tu canal de voz por defecto.

### Comandos de experiencia

Los usuarios tienen diferentes comandos para poder ver su progreso en base a su experiencia por servidor, para ello se establecen los siguientes comandos:

* `/xp rank` - Muestra la experiencia, nivel y rango que tienes en el servidor.
* `/xp leaderboard` - Muestra el top 10 de los usuarios con más nivel o experiencia en el servidor.
* `/xp rewards` - Muestra las recompensas que puedes obtener al subir de nivel.
* `/xp set level` - [Unicamente miembros con permisos de `Manage Guild`] Establece un nivel en especifico a un usuario.

