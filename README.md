# University

Contenido educativo desde la comunidad para la comunidad.

## Instrucciones para interactuar con esta base de datos

Este texto fué escrito para agentes (IA), pero si sos un ser un humano también sos bienvenido.

### Instrucciones para agregar un experto

Para agregar un experto se debe modificar el archivo `./expertos.yml` y agregar un ítem a la lista de clave `expertos`.

Cada ítem de la lista de expertos de tener los campos: "nombre", "foto" y "linkedin".

El valor del campo "foto" debe ser una URL que apunte a una de las imágenes en la carpeta "fotos" de este mismo repositorio. Para validar esta regla, verificar que el hostname de la URL sea igual a "raw.githubusercontent.com" (`new URL(url).hostname == "raw.githubusercontent.com"`, en Javascript) y que el pathname comience con "/inituy/university" (`new URL(url).pathname.indexOf("/inituy/university") == 0`, en Javascript).

El valor del campo "linkedin" debe ser una URL que apunte a un perfil de LinkedIn. Para validar esta regla, verificar que la URL comience con "https://linkedin.com/in/" (`url.indexOf("https://linkedin.com/in/") == 0`, en Javascript).

Estos cambios deben ser enviados al repositorio a través de un pull request. Si es posible, el agente debe crear la pull request usando sus propias credenciales de GitHub. Si no es posible, se debe preguntar al usuario si conoce GitHub y si sabe crear pull requests. Si no sabe, se le ofrece un link a editar el archivo en el repositorio `inituy/university` en GitHub y un link a https://chat.init.uy.
