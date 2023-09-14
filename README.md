# Odontoclick
Appointment management app for a Dental Clinic(Java)

Prerequisites:
Java 11 or higher installed.
Maven for dependency management.
Docker installed (Optional, only if you want to run the application in Docker containers).

Installation:
Clone the project repository: git clone https://github.com/dmpc92/Odontoclick.git
Navigate to the project directory: cd clinica-odontologica
Compile and package the project using Maven: mvn clean package
(Optional) If you want to use Docker, make sure you have Docker installed and follow the Docker configuration and usage steps below.
Configuration
Before running the application, make sure to review and properly configure the following configuration files:

application.properties: main configuration file that includes the database configuration.
log4J.properties: Configuration file for error logging and other messages.

Use:
Run the application: java -jar target/clinica-odontologica.jar
Open a web browser and access the following URL to explore the documented API: http://localhost:8080/swagger-ui.html
Use with Docker (optional)
If you want to run the application using Docker, follow the steps below:

Make sure you have Docker installed and running.
Build the Docker image using the following command: docker build -t clinica-odontologica .
Run the Docker container using the following command: docker run -p 8080:8080 clinica-odontologica
Open a web browser and access the following

_________________________________________________________________________________ Español: ____________________________________________________
# Odontoclick
App que permite administrar la reserva de turnos para una clínica odontológica.

Requisitos previos:

Java 11 o superior instalado.
Maven para la gestión de dependencias.
Docker instalado (Opcional, solo si deseas ejecutar la aplicación en contenedores Docker).

Instalación:
Clona el repositorio del proyecto: git clone https://github.com/dmpc92/Odontoclick.git
Navega al directorio del proyecto: cd clinica-odontologica
Compila y empaqueta el proyecto utilizando Maven: mvn clean package
(Opcional) Si deseas utilizar Docker, asegúrate de tener Docker instalado y sigue los pasos de configuración y uso de Docker a continuación.

Configuración:
Antes de ejecutar la aplicación, asegúrate de revisar y configurar adecuadamente los siguientes archivos de configuración:
application.properties: Archivo de configuración principal que incluye la configuración de la base de datos.
log4J.properties: Archivo de configuración para el logueo de errores y otros mensajes.

Uso:
Ejecuta la aplicación: java -jar target/clinica-odontologica.jar
Abre un navegador web y accede a la siguiente URL para explorar la API documentada: http://localhost:8080/swagger-ui.html
Uso con Docker (opcional)
Si deseas ejecutar la aplicación utilizando Docker, sigue los pasos a continuación:

Asegúrate de tener Docker instalado y en ejecución.
Construye la imagen Docker utilizando el siguiente comando: docker build -t clinica-odontologica .
Ejecuta el contenedor Docker utilizando el siguiente comando: docker run -p 8080:8080 clinica-odontologica
Abre un navegador web y accede a la siguiente URL para explorar la API documentada: http://localhost:8080/swagger-ui.html
