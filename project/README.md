# HOTEL SQLUXE
 ## Video: https://youtu.be/HnPuGIW5AXI

 ## Description:

# **Flask SQL Server App**  

Este proyecto es una aplicación web desarrollada con Flask que interactúa con una base de datos SQL Server utilizando PyODBC. Es ideal para gestionar datos almacenados en una base de datos relacional y se integra con un servidor web simple. 

---

## **Tabla de Contenidos**  
## 1. [Descripción] 
## 2. [Requisitos]
## 3. [Configuración de la Base de Datos] 
## 4. [Ejecuta la aplicación web]
---

## **1-Descripción**  
**A-Contexto y Problemática**
En la actualidad, muchos hoteles enfrentan serias limitaciones al no contar con una base de datos bien estructurada ni con una página web funcional. Esto genera dificultades en áreas clave como:

-Gestión de reservas y habitaciones: El manejo manual o a través de sistemas obsoletos ocasiona errores y pérdidas de información.
-Promoción y alcance: La falta de presencia en línea limita la visibilidad del hotel frente a la competencia.

**B-Solución Propuesta**
Este proyecto es una aplicación web desarrollada con Flask que interactúa con una base de datos SQL Server utilizando PyODBC. Su objetivo es proporcionar una solución integral para gestionar los datos y operaciones esenciales de un hotel utilizando operaciones CRUD por medio del admin dashboard que creamos.

**C-Características de la Aplicación**
-Gestión de datos en tiempo real:
Almacenamiento y manejo eficiente de datos de clientes, reservas, habitaciones y servicios.

-Integración con la base de datos SQL Server:
Conexión mediante PyODBC para garantizar seguridad y eficiencia.

-Interfaz de usuario intuitiva:
Diseño sencillo y accesible para empleados y clientes.

**D-Tecnologías Utilizadas**
Backend: Flask (Python)
Base de Datos: SQL Server
Conexión: PyODBC
Frontend: HTML, CSS, Bootstrap y JavaScript

**E-Beneficios**
Eficiencia Operativa: Automatización de procesos para ahorrar tiempo y reducir errores.
Seguridad: Almacén centralizado de datos para mitigar riesgos.
Crecimiento Comercial: Mayor visibilidad y capacidad para atraer clientes a través de la plataforma web.
---

## **2-Requisitos**  

Para ejecutar este proyecto, necesitas:  
1. **Python 3.10 o superior**  
2. **Flask**  
3. **PyODBC**  
4. **Microsoft ODBC Driver for SQL Server**  
5. **Ejecutar los archivos TABLASSQLUXE E INSERCIONESSQLUXE en SQL SERVER**  
---
## **3-Configuración de la Base de Datos**
Para que la aplicación funcione correctamente, es necesario configurar la base de datos en SQL Server y asegurarse de que los controladores y scripts estén instalados y ejecutados correctamente. Sigue los pasos a continuación:

**Requisitos Previos**
## Microsoft ODBC Driver for SQL Server:

-Descarga e instala el controlador necesario para que PyODBC pueda conectarse a SQL Server.
-Descargar desde la página oficial de Microsoft.
 
## Acceso a SQL Server:

Instala y configura SQL Server en tu sistema local o accede a un servidor SQL remoto.
Asegúrate de contar con credenciales de acceso (usuario y contraseña) o configurar Autenticación de Windows.

## Pasos para Configurar la Base de Datos
## Conéctate a SQL Server:

Abre SQL Server Management Studio (SSMS) y conéctate al servidor donde se almacenarán los datos.

## Ejecuta el script de creación de tablas:

Localiza el archivo TABLASSQLUXE.sql, que contiene las instrucciones para crear todas las tablas necesarias para el sistema.
En SSMS:
--Ejecuta el script.

## Ejecuta el script de inserciones iniciales:

En SSMS:
--Una vez creadas las tablas, ejecuta el archivo INSERCIONESSQLUXE.sql, que contiene datos iniciales como tipos de habitaciones, servicios, y usuarios.

--En el panel izquierdo de SSMS, expande la base de datos y verifica que las tablas y datos se hayan creado correctamente.

## **4-Ejecuta la apliación web**

## **IMPORTANTE: Tener todos los requirements reflejados en el archivo requirements.txt.**

## Accede al archivo app.py:
-Asegúrate de tener el archivo app.py en tu proyecto. Este archivo debe ser el encargado de inicializar y ejecutar la aplicación Flask.
Ejecuta la aplicación:
Para iniciar la aplicación web, abre la terminal o consola de comandos y navega a la carpeta raíz del proyecto donde se encuentra el archivo app.py
Luego ejecuta el siguiente comando:
python app.py
