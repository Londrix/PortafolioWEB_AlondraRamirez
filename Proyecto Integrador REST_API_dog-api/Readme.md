# Practica Integradora REST_API_dog-api
## Objetivo 
Conocer el funcionamiento básico de REST por medio de la dog-api
## Problema a resolver 
El desconocimiento práctico sobre cómo realizar la integración y comunicación entre sistemas web independientes bajo la arquitectura Cliente-Servidor utilizando el protocolo HTTP. La práctica resuelve la problemática de configurar extensiones del servidor local (cURL) y decodificar estructuras de datos JSON para renderizar contenido multimedia de manera dinámica en el frontend. 
## Tecnologías utilizadas 
•	Lenguaje php <br>
•	Xampp <br>
•	Formularios html <br>
•	Visual studio code <br>
•	Api de https://thedogapi.com/signup <br>

## Conceptos aplicados 
•	Arquitectura REST <br>
•	Consumo de APIs de Terceros<br>
•	Uso de la librería cURL en PHP<br>
•	Formato de Intercambio de Datos JSON (JavaScript Object Notation)<br>
•	Configuración del Servidor Web <br>
 
## Capturas de pantalla
Página con la lista de razas de perros 
 <img width="520" height="776" alt="Captura de pantalla 2026-06-03 141924" src="https://github.com/user-attachments/assets/ba149609-fa20-4c53-9c68-6dbe11bb5aa7" />

Vista cuando se selecciona que aparezcan una sola raza de perro  
 <img width="228" height="612" alt="Captura de pantalla 2026-06-03 141937" src="https://github.com/user-attachments/assets/cdb41f28-2275-46df-adb3-b919eb8cacce" />

## Instrucciones de ejecución 

•	Preparación y habilitación del servidor (XAMPP) <br>
•	Abrir el archivo de configuración del servidor php.ini desde el panel de XAMPP o en Visual Studio Code. <br>
•	Buscar la línea ;extension=curl y asegurarse de remover el punto y coma (;) para habilitar la extensión cURL, permitiendo que PHP realice peticiones HTTP externas. Guardar los cambios y reiniciar el servidor Apache. <br>
•	Despliegue del script fuente <br>
•	Crear o colocar la carpeta de la práctica con el archivo PHP desarrollado<br>
•	Autenticación e inserción de la API Key <br>
•	Abrir el código fuente en Visual Studio Code. <br>
•	Localizar la variable de configuración de la cabecera ($apiKey o el parámetro 'x-api-key') y reemplazar el texto de marcador de posición por la clave de API real obtenida previamente desde el portal de The Dog API. <br>
•	Ejecución y Renderizado en el Navegador<br>
•	Abrir el navegador web de preferencia e ingresar la URL local correspondiente al script<br>
•	Al cargar la página, el script inicializará la transferencia cURL de forma transparente para el usuario. El sistema enviará de forma segura la petición GET a los endpoints de la API, decodificará la estructura JSON entrante y desplegará en la interfaz la Lista de Razas de Perros con sus respectivos IDs junto con las Imágenes de la raza Husky en tiempo real. <br>

## Reflexión final 
La realización de esta práctica integradora me permitió comprender el funcionamiento de la arquitectura REST y cómo interactúan los sistemas web entre sí. Aprendí a utilizar la librería cURL en PHP para realizar peticiones HTTP (GET), el uso seguro de API Keys y la manipulación de datos JSON para renderizarlos dinámicamente en el frontend. 
Lo que se me dificultaron, el principal reto fue comprender la estructura de los arreglos multidimensionales devueltos por la API y asegurar la correcta configuración de las cabeceras (headers) para evitar el rechazo de la petición. 
Finalmente, como parte de mi mejora continua, me gustaría mejorar la interfaz visual y agregar un buscador o menú desplegable dinámico para que el usuario pueda seleccionar cualquier raza en tiempo real, en lugar de dejar un ID fijo en el código.
