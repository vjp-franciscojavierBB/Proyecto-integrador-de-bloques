Análisis de Wikipedia en español

Integrantes

Kevin Núñez Sánchez

Javier Becerro Batuecas

Descripción del caso

En este trabajo analizamos Wikipedia en español, una enciclopedia en línea. Observamos cómo se carga un artículo en el navegador y cómo se comunican el navegador y los servidores de Wikipedia.

El artículo analizado es **Batalla de las Termópilas**.  
URL: https://es.wikipedia.org/wiki/Batalla_de_las_Term%C3%B3pilas

Recorrido de una petición

El usuario abre el artículo en el navegador.

El navegador solicita la página y los recursos necesarios para mostrarla.

Los servidores de Wikipedia responden a esas peticiones.

El navegador procesa las respuestas y muestra el artículo.

Esquema:

Usuario abre un artículo
        ↓
Navegador (cliente / frontend)
        ↓ peticiones HTTP para la página y sus recursos
Servidores de Wikipedia
        ↓ respuestas HTTP
Navegador procesa las respuestas y muestra el artículo

Reparto entre frontend y backend

Frontend (navegador)

Muestra el artículo y los controles de la página.

Solicita los recursos necesarios para mostrar el contenido.

Procesa las respuestas recibidas y las presenta al usuario.

Backend (servidores)

Recibe las peticiones del navegador.

Devuelve el contenido del artículo y los recursos solicitados.

Envía respuestas HTTP que el navegador procesa para mostrar la página.

Análisis de tres peticiones HTTP

Los datos de esta tabla deben copiarse de DevTools → Red / Network. Elegid tres peticiones realizadas al cargar o utilizar el artículo.

N.º

Recurso o URL (resumida)

Método

Código de estado

Content-Type

¿Qué recurso carga?

1

[completar]

[completar]

[completar]

[completar]

[explicar brevemente]

2

[completar]

[completar]

[completar]

[completar]

[explicar brevemente]

3

[completar]

[completar]

[completar]

[completar]

[explicar brevemente]

Cómo obtuvimos los datos

Abrimos el artículo elegido en Wikipedia en español.

Abrimos las herramientas de desarrollador con F12 y seleccionamos Red / Network.

Recargamos la página.

Seleccionamos tres peticiones y anotamos el método, el código de estado y el encabezado Content-Type.

Guardamos una captura de DevTools donde se vean las peticiones y sus datos.

Captura de DevTools

Guardamos la captura en capturas/peticiones-devtools.png.



Conclusión

Al cargar un artículo de Wikipedia, el navegador realiza peticiones HTTP a los servidores para obtener la página y los recursos que necesita. Las respuestas incluyen distintos tipos de contenido, que el navegador procesa para mostrar el artículo. Con DevTools podemos observar detalles de esas comunicaciones, como el método, el estado HTTP y el tipo de contenido.



Referencias

- [Wikipedia en español](https://es.wikipedia.org/)
- [Artículo: Batalla de las Termópilas](https://es.wikipedia.org/wiki/Batalla_de_las_Term%C3%B3pilas)
