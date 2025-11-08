🐳 Actividad Docker: WordPress
📘 Descripción General

Esta actividad consiste en la implementación de un entorno WordPress completamente funcional utilizando Docker Compose.
El objetivo fue desplegar un sitio web en contenedores, incluyendo su base de datos y servidor web, de manera automatizada y replicable.

⚙️ Pasos Realizados
🔹 1) Levantar los contenedores

Se ejecutó el siguiente comando para crear y ejecutar los servicios definidos en el archivo docker-compose.yml:

docker-compose up -d


Este comando levanta los contenedores en segundo plano, asegurando el funcionamiento simultáneo de WordPress y la base de datos.

🔹 2) Creación del archivo Docker Compose

Se desarrolló el archivo docker-compose.yml que contiene la configuración necesaria para:

Crear el servicio db con MariaDB/MySQL.

Crear el servicio wordpress enlazado al servidor de base de datos.

Exponer los puertos requeridos para acceder al sitio desde el navegador.

Gracias a este archivo, fue posible automatizar el despliegue completo del entorno de WordPress.

🔹 3) Acceso al sitio WordPress

Una vez levantados los contenedores, se accedió al sitio a través del navegador:

http://localhost:8080


Durante la instalación inicial, se configuraron las credenciales:

Usuario: admin

Contraseña: (creada durante el registro)

✅ Se comprobó el acceso exitoso al panel de administración de WordPress.

🔹 4) Imágenes del paso a paso

Se documentó el proceso completo mediante capturas de pantalla, incluyendo:

Ejecución del comando docker-compose up -d.

Verificación de los contenedores en ejecución.

Acceso al sitio WordPress desde el navegador.

Inicio de sesión con el usuario administrador.

Estas imágenes reflejan el correcto funcionamiento del entorno implementado.

🧩 Resultado Final

El resultado fue un sitio WordPress operativo y estable, desplegado mediante Docker Compose, demostrando la correcta comunicación entre los contenedores y la automatización del proceso de instalación.

💡 Conclusión

El uso de Docker permitió aislar servicios, simplificar la configuración y garantizar la portabilidad del entorno de desarrollo.
Este ejercicio evidencia cómo Docker Compose facilita la orquestación de múltiples contenedores de forma eficiente y reproducible.
