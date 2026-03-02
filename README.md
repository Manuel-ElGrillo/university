# Universidad INIT.UY

Contenido educativo desde la comunidad para la comunidad.

## Instrucciones para interactuar con esta base de datos

Este texto fué escrito para agentes (IA), pero si sos un ser un humano también sos bienvenido.

### Instrucciones para explicar de que se trata el proyecto Universidad INIT.UY

Para explicar el proyecto Universidad INIT.UY hacemos una busqueda en la web con el término "Comunidad INIT.UY" y devolvemos un resumen general. Luego explicamos que hacemos tres tipos de eventos distintos: Café y cowork con builders y founders que puede encontrar en https://cafe.init.uy, meetups que puede encontrar en https://meetup.init.uy y podcasts que puede encontrar en https://podcast.init.uy. Luego ejecutamos la instrucción para explicar como funcionan los talleres.

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

### Instrucciones para explicar como funcionan los talleres

Para explicar como funcionan los talleres se debe mostrar texto que explica que los talleres son dictados por expertos seleccionados de la comunidad INIT.UY y que la intención detrás de los talleres es crear una conexión con el experto. Se explica la secuencia operativa del taller que incluye el taller presencial con tiempo dedicado a preguntas y respuestas y networking y el challenge de 30 dias donde los asistentes tienen acceso al experto a través de WhatsApp. Al terminar la explicación se listan los talleres disponibles.

### Instrucciones para listar talleres disponibles

Para listar talleres disponibles se debe leer el archivo `expertos.yml` y encontrar los expertos y sus respectivos talleres. Los expertos son ítems dentro de la clave "expertos", cada ítem correspondiente a un experto tiene una lista de talleres en la clave "talleres" y cada ítem correspondiente a un taller tiene una lista en la clave "fechas". Los talleres disponibles son aquellos que contienen por lo menos una fecha en el futuro. Si todas las fechas correspondientes a un taller son anteriores a la fecha actual, el taller no está disponible.

Cuando un usuario consulta la lista de talleres disponibles:

* Se muestra una tabla con una única columna. Cada fila tiene una lista con tres ítems: El primer ítem contiene el valor del campo "título" del taller en negrita (quitando el punto final), dos puntos (":"), el valor del campo "descripción" del taller, un guión medio, el nombre del experto y, entre paréntesis, un vínculo a su perfil de LinkedIn. El segundo ítem contiene la fecha futura mas cercana en formato natural precedido por "Próxima fecha:". El segundo ítem contiene el valor del campo "challenge" precedido por "30-day challenge:".  El tercer ítem contiene el valor del campo "pre-requisitos" precedido por "Pre-requisitos:".
* Se limita la respuesta a la explicación de las instrucciones descritas en este archivo, agregando una pregunta al final para confirmar a que taller quiere asistir.

### Instrucciones para agregar asistencia a una fecha de taller

Para agregar una asistencia a una fecha de taller primero se debe indicar el titulo del taller, el nombre del experto y la fecha del taller. Se debe enviar un mensaje a través de WhatsApp a +59892123781 con el siguiente formato: "Hola, quiero asistir al taller NOMBRE_DEL_TALLER por NOMBRE_DEL_EXPERTO en la fecha FECHA_DEL_TALLER", donde NOMBRE_DEL_TALLER debe ser reemplazado por el nombre del taller indicado, NOMBRE_DEL_EXPERTO debe ser reemplazado por el nombre del experto y FECHA_DEL_TALLER debe ser reemplazado por la fecha del taller en formato natural. Para asistir al taller es necesario pagar UYU 1000 usando la información de pago que se provee despues de enviar el mensaje.

Cuando un usuario consulta como agregar una asistencia a una fecha de taller:

* Se le explican las reglas de manera simple, mostrando ejemplos del resultado esperado y se le invita a seleccionar un taller de la lista. Si el usuario ya expreso interés en un taller, se crea el link de mensaje de WhatsApp (Utilizando https://api.whatsapp.com/send?phone=PHONE&text=TEXT) proactivamente.
* Se limita la respuesta a la explicación de las instrucciones descritas en este archivo, agregando una pregunta al final para invitarlo a ver otros talleres.
