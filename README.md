Descripción
Este proyecto es un software de escritorio desarrollado en Java utilizando JavaFX para la interfaz gráfica. El objetivo principal es ofrecer una herramienta visualmente atractiva y funcional para gestionar la economía personal (entradas y salidas de dinero) con persistencia de datos.

El proyecto implementa el patrón de arquitectura MVC (Modelo-Vista-Controlador) para asegurar un código limpio, escalable y mantenible.

 Características Principales
Alta de Movimientos: Registro rápido de ingresos (Verde) y gastos (Rojo).

Cálculo en Tiempo Real: Balance total actualizado automáticamente.

Interfaz Moderna: Diseño "Dark Mode" personalizado con CSS (estética Cyberpunk/Neon).

Persistencia de Datos: Guardado automático en archivo local (.csv), los datos no se pierden al cerrar.

Gestión de Estados: Botón de reinicio con sistema de seguridad (alertas de confirmación).

Feedback Visual: Colores dinámicos en la tabla según el tipo de transacción.

 Tecnologías Utilizadas
Lenguaje: Java 17 / 21

Interfaz (GUI): JavaFX

Gestión de Dependencias: Maven

Estilos: CSS3 (integrado en JavaFX)

Persistencia: Java I/O (Manejo de archivos CSV)

IDE: Eclipse

 Arquitectura del Proyecto (MVC)
El código está organizado en paquetes para separar responsabilidades:

logica: Contiene las clases Modelo (Movimiento, Gestion) que manejan los datos y reglas de negocio.

vista: Contiene la interfaz gráfica (App, estilos.css) construida con JavaFX.

controller: Actúa como intermediario (Controller) conectando la vista con la lógica.

Cómo ejecutar el proyecto
Puedes descargar el archivo .jar desde la sección de Releases o compilarlo tú mismo.

Requisitos
Tener instalado Java (JRE o JDK) versión 17 o superior.

Ejecución
Descarga el archivo GestorFinal.jar y haz doble clic, o ejecuta el siguiente comando en tu terminal:

Bash

java -jar GestorFinal.jar


Descripción corta del repo: Cuando crees el repositorio, en la descripción corta pon: "Aplicación de escritorio JavaFX con patrón MVC, persistencia de datos y diseño UI personalizado con CSS."
