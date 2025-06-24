
# Título del proyecto

Centro de adopción de gatitos


## Autores

-  León Jardines Alexis
-  Mejía Ugalde Sabrina Elizabeth 
-  Patricio Flores Alex 



## Overview

El código de este proyecto es acerca de una página web para un centro de adopción de gatitos, contanto con tres módulos principales:

1. El módulo para el "administrador"
2. El módulo para el "empleado"
3. El módulo para el "usuario"


* Todos previamente registrados y con control de acceso mediante un "login". 
* Las caracteristicas para cada módulo cambian para cada uno de los tres diferentes usuraios:
    1. Caracteristicas como "adopción", "voluntario" y "contacto" pertenecen al módulo "usuario".
    2. "editar usuarios", "ver mensajes" y "ver solicitudes de adopción" pertenecen al módulo "administrador"
    3. Finalmente, "ver y agregar gatitos" y "revisión de mensajes y solicitudes" pertenecen a módulo "empleado".

* El acceso "login", cuenta con opción para recordar al ultimo usuario en ingresar al sistema y un botón para registrar nuevos usuarios. 
## Especificaciones técnicas

* Compatible con sistemas operativos:
1. Windows (Windows 10 en adelante)
2. Linux (Ubuntu 20.04 en adelante, Debian 11 y 12,)
3. macOS (12 en adelante)

* Memoria RAM:
2 GB de memoria RAM mínima, 4GB de memoria RAM deseable

* Servidor web :
Internet Information Services (IIS) de Windows®

* PHP:
Versión 7.4.
Compatible hasta 8.2

* Base de datos:
MySQL.
La base de datos se llama "refugio" y contiene, entre otras, las siguientes tablas:

Tablas:          |    Descripción                                  

"contactos" |    Mensajes enviados desde el formulario        
"gatitos"      |    Información de gatos disponibles              
"registro"    |    Usuarios registrados con roles y credenciales 

Puedes cargar la estructura completa con el archivo: refugio.sql

* Navegador:
Cualquier navegador moderno (Chrome, Firefox, Edge, etcétera)

## Librearias

1. FPDF: Para la generación de archivos PDF.

2. SweetAlert2: Para alertas interactivas.

3. MySQLi: Extensión para la conexión con la base de datos.

4. Bootstrap: Para una interfaz visual atractiva.

5. HTML5: Usado en el formularios y botones.


## ¿Cómo funciona?
1. Copia la carpeta del proyecto en en tu servidor local (IIS)
2. crea la base de datos (refugio.sql)
 (Nota: Asegura de configurar la conexión en los archivos con tus propias credenciales para tu propia base de datos)

3. Accede al proyecto desde tu navegador: http://localhost/Refugio_ultimo


