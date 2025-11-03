# Tutorial: Proyecto con un servidor web y base de datos

Este tutorial documenta paso a paso la creación y configuración de un servidor web (PHP + Apache) y un servidor de base de datos (MariaDB) usando Docker. Cada paso incluye la captura de pantalla correspondiente, ordenada cronológicamente.

---

## 1. Descarga de imágenes Docker

Se descargan las imágenes necesarias para el proyecto.
![Descarga de imágenes](./images/Captura_de_pantalla_2025-11-03_15-58-06.png)

---

## 2. Visualización de imágenes descargadas

Se muestran las imágenes disponibles en el sistema.
![Imágenes descargadas](./images/Captura_de_pantalla_2025-11-03_15-58-24.png)

---

## 3. Creación del contenedor web (php:7.4-apache)

Se crea el contenedor en modo demonio.
![Contenedor web creado](./images/Captura_de_pantalla_2025-11-03_15-59-03.png)

---

## 4. Comprobación del tamaño del contenedor web

Se verifica el espacio ocupado por el contenedor.
![Tamaño contenedor web](./images/Captura_de_pantalla_2025-11-03_15-59-45.png)

---

## 5. Copia de info.php al contenedor

Se copia el archivo info.php al directorio raíz del servicio web.
![Copia de info.php](./images/Captura_de_pantalla_2025-11-03_16-00-33.png)

---

## 6. Comprobación del espacio ocupado tras copiar archivos

Se vuelve a comprobar el tamaño del contenedor.
![Tamaño tras copiar archivos](./images/Captura_de_pantalla_2025-11-03_16-01-01.png)

---

## 7. Acceso a info.php desde el navegador

Se accede al archivo info.php desde el navegador web.
![info.php en navegador](./images/Captura_de_pantalla_2025-11-03_16-06-10.png)

---

## 8. Creación y acceso a index.html

Se crea el archivo index.html y se accede desde el navegador.
![index.html en navegador](./images/Captura_de_pantalla_2025-11-03_16-09-17.png)


---

## 9. Creación y acceso a index.php

Se crea el archivo index.php y se accede desde el navegador.
![index.php en navegador](./images/Captura_de_pantalla_2025-11-03_16-07-16.png)

---

## 10. Acceso a index.php tras ajustes

Se comprueba el acceso correcto tras ajustes en el contenedor.
![index.php acceso correcto](./images/Captura_de_pantalla_2025-11-03_16-09-38.png)

---

## 11. Arranque del contenedor MariaDB y conexión desde cliente externo

Se arranca el contenedor de base de datos y se conecta desde un cliente externo para verificar la base de datos creada.
![Conexión a MariaDB](./images/Captura_de_pantalla_2025-11-03_16-08-02.png)

---

## 12. Verificación de base de datos creada

Se muestra la base de datos 'prueba' creada automáticamente.
![Base de datos prueba](./images/Captura_de_pantalla_2025-11-03_16-13-27.png)

---

## 13. Error al intentar borrar la imagen mariadb con el contenedor activo

Se intenta borrar la imagen mariadb y se documenta el error.
![Error borrar mariadb](./images/Captura_de_pantalla_2025-11-03_16-13-49.png)

---

## 14. Comprobación final del entorno

Se realiza una comprobación final del entorno y los contenedores.
![Comprobación final](./images/Captura_de_pantalla_2025-11-03_16-09-57.png)

---

## 15. Estado final y cierre del proyecto

Se documenta el estado final y cierre del proyecto.


---

**Autor:** Xisco Rosselló
**Fecha:** 3 de noviembre de 2025
