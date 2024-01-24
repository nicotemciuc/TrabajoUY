# Descripción del Proyecto: Sistema de Gestión Laboral

## Descripción

Este proyecto, desarrollado como parte del Taller de Programación, es una aplicación robusta implementada en Java que utiliza WebServices, JSP, y sigue la arquitectura MVC. La aplicación proporciona una plataforma integral para la gestión de empleo, permitiendo a empresas y candidatos interactuar de manera eficiente en el proceso de búsqueda de trabajo.

## Características Principales

- **Registro de Usuarios:** Los usuarios pueden registrarse como empresas o postulantes, brindando flexibilidad en la participación.

- **Autenticación:** La aplicación ofrece un sistema seguro de autenticación, permitiendo a los usuarios acceder a sus cuentas de manera segura.

- **Publicación de Ofertas Laborales:** Las empresas pueden publicar oportunidades laborales, detallando los requisitos y descripciones del trabajo.

- **Postulación a Ofertas:** Los postulantes tienen la capacidad de postularse a las ofertas laborales publicadas, facilitando el proceso de aplicación.

- **Estación de Trabajo Administrativa:** Se ha desarrollado una estación de trabajo en Swing que actúa como servidor central. Los administradores pueden acceder a información detallada sobre todas las ofertas, usuarios y otros objetos relevantes.

- **Compra de Paquetes para publicar multiples ofertas laborales a un menor precio**: Las empresas tienen la oportunidad de comprar paquetes que permiten la publicacion de multiples ofertas a un menor coste.


## Estructura del Proyecto

El código sigue una estructura organizada que refleja la arquitectura MVC. La separación de la lógica de negocio (Modelo), la presentación (Vista) y el control (Controlador) mejora la mantenibilidad y escalabilidad del sistema.

## Tecnologías Utilizadas

- **Java:** El núcleo del proyecto se ha desarrollado en Java, aprovechando su versatilidad y robustez.

- **WebServices y JSP:** Se han utilizado servicios web y JSP para la implementación de la interfaz de usuario web y la comunicación eficiente entre el servidor central y el servidor web.

- **Interfaz Web con CSS, JS, Bootstrap y JQuery:** Las páginas web se han creado utilizando tecnologías web como CSS, JS y Bootstrap para ofrecer una experiencia de usuario moderna y receptiva. También para las busquedas se ha aplicado JQuery/AJAX

- **Swing:** La estación de trabajo administrativa se ha construido utilizando la biblioteca Swing, proporcionando una interfaz gráfica de usuario intuitiva para los administradores.

## Instrucciones de Uso

Para poder ejecutar de manera correcta TODO:

    1 - Ejecutar: make compilar
    2 - En la carpeta paquete ejecutar:  java -jar estacionTrabajo.jar
    3 - Colocar servidorWeb.war en la carpeta webapps de apacheTomcat
    4 - Ejecutar para iniciar el servidor el comando sh startup.sh en la carpeta bin de apacheTomcat y ejecutar sh shutdown.sh para cerrarlo
