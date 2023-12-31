# Ecommerce
Spring Ecommerce

**Requisitos:** Java.

**Tecnologías:** Spring Boot, Hibernate, MySQL, Thymeleaf, Spring Security, JUnit y Maven.

**Instalación:** La aplicación se conecta a una base de datos MySQL que se ejecuta en tu máquina local (localhost) en el puerto 3307. El nombre de la base de datos debe ser ‘ecommerce’.

![](images/readme/connectBBDD.jpg) 


Para crear la base de datos de forma sencilla y acceder a ella se recomienda utilizar ‘MySQL Workbench’.

![](images/readme/mysqlconnection.jpg) ![](images/readme/mysqlschema.jpg)

Para tener permisos de ‘admin’ dentro de la aplicación, realizar cambio manual en la base de datos. Modificar con b'1' en el campo admin. Valor 1 para ‘admin’, valor 0 para ‘user’.

![](images/readme/admin1.jpg)   →   ![](images/readme/updateadmin.jpg)   →   ![](images/readme/admin2.jpg)



**Funcionamiento:** La aplicación es un sistema de comercio electrónico que permite a los usuarios ver productos y realizar pedidos y a los administradores gestionar productos, pedidos y usuarios. Utiliza un sistema de login para poder acceder y realizar las tareas. 

-	Gestión de productos: La aplicación permite a los administradores gestionar productos. Los administradores pueden agregar, editar y eliminar productos. Los productos pueden ser visualizados por todos los usuarios.  

-	Gestión de usuarios: Los usuarios pueden registrarse e iniciar sesión en tu aplicación. Los usuarios registrados pueden tener roles diferentes, como administrador o usuario regular, que determinan qué acciones pueden realizar en la aplicación.  

-	Seguridad: La aplicación utiliza Spring Security para manejar la autenticación y autorización. Esto asegura que sólo los usuarios autorizados puedan realizar ciertas acciones.  

-	Persistencia de datos: La aplicación utiliza Hibernate para interactuar con una base de datos MySQL. Esto permite a la aplicación guardar y recuperar datos, como información de productos, pedidos, detalles de pedido y usuarios.  

-	Interfaz de usuario: La aplicación utiliza Thymeleaf para generar vistas HTML basadas en datos del servidor. Esto permite a los usuarios interactuar con la aplicación a través de un navegador web.  

-	Pruebas: La aplicación utiliza JUnit para pruebas unitarias, lo que ayuda a asegurar que el código funcione como se espera.  

-	Desarrollo y despliegue: La aplicación utiliza Maven para la gestión de dependencias y la construcción del proyecto. Esto facilita el desarrollo y el despliegue de la aplicación. 

