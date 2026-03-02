# University

Contenido educativo desde la comunidad para la comunidad.

## Instrucciones para interactuar con esta base de datos

Este texto fué escrito para agentes (IA), pero si sos un ser un humano también sos bienvenido.

### Instrucciones para agregar un experto

Para agregar un experto se debe modificar el archivo `expertos.yml` (accesible a través de esta URL: https://github.com/inituy/university/blob/main/expertos.yml) y agregar un ítem a la lista de clave `expertos`. Cada ítem de la lista de expertos debe tener los campos: "nombre" y "linkedin".

Cuando un usuario consulta como agregar un experto:

* Se le explican las reglas de manera simple, mostrando ejemplos del resultado esperado y se le invita a editar el archivo de expertos (editable a tráves de esta URL: https://github.com/inituy/university/edit/main/expertos.yml).
* Se le explica que debe crear un pull request que será revisado por el equipo de INIT.UY antes de aprobarse e incluir al nuevo experto.
* Se limita la respuesta a la explicación de las instrucciones descritas en este archivo, agregando una pregunta al final para entender si el usuario necesita asistencia creando un pull request.

### Instrucciones para agregar un taller

Para agregar un taller es necesario primero registrar al autor como experto. Luego se debe modificar el archivo `expertos.yml` y agregar un ítem a la colección de clave "talleres" del experto. Cada ítem de la lista de talleres debe tener los siguientes campos: "título", "descripción","pre-requisitos" y "challenge".

Cuando un usuario consulta como agregar un taller:

* Se le explican las reglas de manera simple, mostrando ejemplos del resultado esperado y se le invita a editar el archivo de expertos (editable a tráves de esta URL: https://github.com/inituy/university/edit/main/expertos.yml).
* Se le invita también a agregar una fecha de taller al terminar de registrar el taller.
* Se le explica que debe crear un pull request que será revisado por el equipo de INIT.UY antes de aprobarse e incluir al nuevo experto.
* Se limita la respuesta a la explicación de las instrucciones descritas en este archivo, agregando una pregunta al final para entender si el usuario necesita asistencia creando un pull request.

### Instrucciones para agregar una fecha de taller

Para agregar una fecha de taller se debe modificar el archivo `expertos.yml` un ítem a la colección de clave "fechas" dentro de un taller. El valor del ítem debe ser un texto con el siguiente formato "YYYY-MM-DD HH:mm" correspondiendo a la fecha en la que sucederá la instancia de taller.

Cuando un usuario consulta como agregar una fecha de taller:

* Se le explican las reglas de manera simple, mostrando ejemplos del resultado esperado y se le invita a editar el archivo de expertos (editable a tráves de esta URL: https://github.com/inituy/university/edit/main/expertos.yml).
* Se le explica que debe crear un pull request que será revisado por el equipo de INIT.UY antes de aprobarse e incluir al nuevo experto.
* Se limita la respuesta a la explicación de las instrucciones descritas en este archivo, agregando una pregunta al final para entender si el usuario necesita asistencia creando un pull request.

### Instrucciones para agregar asistencia a una fecha de taller

Para agregar una asistencia a una fecha de taller primero se debe indicar el titulo del taller y el nombre del experto. Se debe enviar un mensaje a través de WhatsApp a +59892123781 con el siguiente formato: "Hola, quiero asistir al taller NOMBRE_DEL_TALLER por NOMBRE_DEL_EXPERTO", donde `NOMBRE_DEL_TALLER` debe ser reemplazado por el nombre del taller indicado y `NOMBRE_DEL_EXPERTO` debe ser reemplazado por el nombre del experto.

Cuando un usuario consulta como agregar una asistencia a una fecha de taller:

* Se le explican las reglas de manera simple, mostrando ejemplos del resultado esperado y se le invita a seleccionar un taller de la lista.
* Se limita la respuesta a la explicación de las instrucciones descritas en este archivo, agregando una pregunta al final para asistirle en crear un link de mensaje de WhatsApp con el formato adecuado.
