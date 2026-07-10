# SISTEMA-INTEGRAL-DE-COMUNICACIONES-Y-ELECTRONICA-SICE
<img width="1600" height="1600" alt="logosice" src="https://github.com/user-attachments/assets/c2c439c6-0a34-422d-9a9b-7ca8c7f3b6b1" />
Proyecto de transformación digital para la Jefatura de Ingeniería en Comunicaciones y Electrónica (ESIME Zacatenco, IPN). Sistema diseñado para optimizar, centralizar y modernizar los procesos internos mediante herramientas tecnológicas.
# Transformación Digital - Jefatura ICE (SICE)

Este repositorio contiene el código fuente del Sistema de Información (anteriormente SICAH, en transición a SICE), desarrollado como parte del proceso de transformación digital para la Jefatura del programa de Ingeniería en Comunicaciones y Electrónica en la ESIME Zacatenco, IPN.

##  Objetivo del Proyecto
El propósito principal de este sistema es aprovechar las herramientas tecnológicas actuales para digitalizar y automatizar los procesos administrativos y operativos de la jefatura. Buscamos reducir los tiempos de respuesta, minimizar el uso de papel y centralizar la información para una gestión más eficiente.

## Características Principales
*   **Digitalización de Procesos:** Transición de los trámites y registros físicos a un entorno completamente digital.
*   **Gestión Centralizada:** Un único punto de acceso para la administración de la información interna.
*   **Despliegue Local:** Configurado para ejecutarse en servidores internos utilizando un entorno XAMPP (Apache/MySQL).

## Tecnologías Utilizadas
*   **Servidor Web:** Apache (vía XAMPP)
*   **Base de Datos:** MySQL
*   **Lenguaje Backend:** PHP
*   **Frontend:** HTML, CSS, JavaScript
  
## Instalación Local (Para el equipo de desarrollo)
1. Clonar el repositorio en la carpeta `htdocs` de XAMPP:
   `git clone https://github.com/tu-usuario/sicah-web.git`
2. Asegurar que la carpeta raíz tenga el nombre correcto configurado en el servidor.
3. Importar la base de datos local proporcionada por el administrador en `phpMyAdmin`.
4. Iniciar los módulos de Apache y MySQL en el Panel de Control de XAMPP.
5. Acceder vía navegador local apuntando al puerto configurado (ej. `http://localhost:8080/sicah-web/`).
