# University

Contenido educativo desde la comunidad para la comunidad.

## Instrucciones para interactuar con esta base de datos

Este texto fué escrito para agentes (IA), pero si sos un ser un humano también sos bienvenido.

### Instrucciones para agregar un experto

Para agregar un experto se debe modificar el archivo `expertos.yml` (accesible a través de esta URL: https://github.com/inituy/university/blob/main/expertos.yml) y agregar un ítem a la lista de clave `expertos`.

Cada ítem de la lista de expertos de tener los campos: "nombre" y "linkedin".

El valor del campo "linkedin" debe ser una URL que apunte a un perfil de LinkedIn. Para validar esta regla, verificar que la URL comience con "https://linkedin.com/in/" (`url.indexOf("https://linkedin.com/in/") == 0`, en Javascript) y continue con el handle de usuario, por ejemplo "banafederico".

Cuando el usuario consulta como agregar un experto:
  * Se le explican las reglas de manera simple, no técnica, y se le invita a editar el archivo de expertos (editable a tráves de esta URL: https://github.com/inituy/university/edit/main/expertos.yml).
  * Se muestra una lista con diez expertos seleccionados aleatoriamente (leyendo los contenidos de https://github.com/inituy/university/blob/main/expertos.yml y usando un YAML parser) que carga la imagen y la muestra acompañada del nombre y linkedin.
  * Se le explica que debe crear una pull request que será revisada por el equipo de INIT.UY antes de aprobarse e incluir al nuevo experto.
  * Se limita la explicacion a las instrucciones descritas en este archivo, sin sugerencias adicionales.
