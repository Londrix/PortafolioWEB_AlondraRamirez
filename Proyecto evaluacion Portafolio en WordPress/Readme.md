# Portafolio en WordPress
## Objetivo 
Diseñar un sitio web tipo portafolio utilizando WordPress, aplicando conocimientos sobre instalación, configuración, estructura de menús, páginas, entradas, temas y personalización básica. 
## Problema a resolver 
El problema que resuelve es uno para nosotros mismos, en el que ya tendríamos preparado un portafolio profesional con un CV incluido para cuando tengamos que salir al mundo laboral y mostrar nuestros conocimientos. 
## Tecnologías utilizadas 
•	Wordpress 
## Conceptos aplicados 
Para este trabajo incluye los conocimientos adquiridos sobre la arquitectura Modelo-Vista-Controlador. La utilización del lenguaje php como backend de un sistema. La práctica adquirida en trabajos anteriores sobre la organización en html y se aplicó en este proyecto y la utilización del gestor de mysql de phpmyadmin y como conectar tu código a esa base de datos. 
 
## Capturas de pantalla
Página sobre mi
 <img width="1234" height="698" alt="Captura de pantalla 2026-06-03 135211" src="https://github.com/user-attachments/assets/e60e61bc-4711-478f-b234-817de19d5255" />

Servicios que se ofrecen 
<img width="1274" height="693" alt="Captura de pantalla 2026-06-03 135222" src="https://github.com/user-attachments/assets/09c3c64b-5c0c-49dd-888a-538d23002881" />

Portafolio (trabajos realizados) 
 <img width="1199" height="700" alt="Captura de pantalla 2026-06-03 135231" src="https://github.com/user-attachments/assets/45d2ebe8-2657-4cfd-9cca-282a97442c7f" />

Vista de contacto
<img width="1160" height="667" alt="Captura de pantalla 2026-06-03 135239" src="https://github.com/user-attachments/assets/5a5d32dd-5309-4eae-a7d9-c86599a5c01d" />


## Instrucciones de ejecución 
Preparación del entorno local (XAMPP): <br>
•	Iniciar el Panel de Control de XAMPP y activar los servicios de Apache y MySQL. <br>
•	Asegurarse de que la carpeta descomprimida de WordPress esté correctamente ubicada en el directorio raíz de servidor: <br>
Configuración de la Base de Datos en phpMyAdmin:<br>
•	Acceder al gestor local mediante la URL <br>
•	Crear una base de datos llamada wordpress seleccionando el cotejamiento utf8_spanish_ci. <br>
•	Dirigirse a la pestaña Usuarios, seleccionar Agregar usuario y registrar las credenciales del sistema (Nombre de usuario: u_wordpress junto con una contraseña segura). <br>
•	En la sección de privilegios específicos, seleccionar la base de datos wordpress, hacer clic en Marcar todo para otorgar todos los permisos y guardar los cambios. <br>
Enlazado del Archivo de Configuración:<br>
•	Abrir el directorio del proyecto en Visual Studio Code, renombrar el archivo wp-config-sample.php a wp-config.php y editar las variables de entorno (DB_NAME, DB_USER, DB_PASSWORD, y DB_HOST como localhost) con los datos del usuario y la base de datos creados. <br>
Ejecución del Script de Instalación:<br>
•	Abrir el navegador web e ingresar a la dirección de instalación: http://localhost/wordpress/wp-admin/install.php. <br>
•	Completar los campos del famoso asistente de 5 minutos asignando el título al sitio ("Portafolio de Alondra"), correo electrónico, y definir el usuario administrador (admin) para la gestión interna. <br>
Navegación e Interacción con el Portafolio (Vista de Usuario):<br>
•	Una vez finalizada la instalación, acceder a la URL raíz para visualizar e interactuar con la interfaz del portafolio estático. <br>
•	El usuario podrá navegar mediante el menú principal por las páginas de Inicio, Sobre mí, Servicios, Portafolio (donde se despliegan los proyectos con sus respectivos enlaces a GitHub) y realizar pruebas de envío de correo en la sección de Contacto. <br>

## Reflexión final 
La realización de este proyecto final de la tercera unidad me permitió recapitular mis conocimientos sobre los wireframes y su correcta organización. Aunque ya conocía anteriormente el software de WordPress, nunca había recurrido a su uso práctico. Gracias a este trabajo, pude comprender el amplio mundo que abarca WordPress, sus funcionalidades, plantillas, plugins y la facilidad de crear sitios web sin la necesidad de programar. Una de las mayores dificultades que enfrenté en el desarrollo del portafolio fue comprender el funcionamiento de WordPress y la edición de la información en los temas descargados. Como parte de mi mejora continua, queda pendiente practicar e investigar más sobre la edición correcta en este sitio para perfeccionar el diseño de mis futuras páginas web. 
