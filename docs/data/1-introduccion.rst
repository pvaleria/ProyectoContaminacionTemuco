Introduccion
=================================

Nombre del proyecto:
--------------------------
                Sistema de Monitorio Contaminación Temuco (SMCT)

La Arquitectura de software nos permite solucionar la complejidad que requieren distintos sistemas para su solución, en este proyecto se desea crear una pagina web que permite a un usuario visualizar gráficas sobre variables medioambientales relacionadas con contaminación.

Para llevar a cabo la construcción del sistema se utilizara la metodología Ad-Hoc, la cual es iterativa y consiste en primer lugar definir el stakeholder el cual es la persona interesada en el sistema luego se define la Visión, Objetivos y Áreas la cual por cada una se definen las historias de usuario correspondiente, se selecciona alguna y se define su diseño gráfico (mockup), se realizan los diseños correspondientes con lenguajes de modelado arquitectura y procesos adecuados, para este trabajo se utilizara UML, C4 y Archimate luego se lleva a la fase de implementan para finalizar el ciclo el cual se puede repetir las veces que sea necesario. Por otro lado dicha metodología esta centrada en la documentación de cada uno de los pasos.

IMAGEN AD HOC

Para resolver la Arquitectura de Software donde lo que se requiere es graficar distintas variables medioambientales, en primer lugar se deben obtener los datos de alguna base de datos, luego procesarlos para finalmente mostrarlos a través de una interfaz gráfica para ello se utilizara principalmente un  Modelo VIsta Controlador (MVC) y la estructura general se separa en dos partes principales:

Backend(Lo que no se ve): Para resolver el modelo, los datos y el controlador se utlizara el Framwork Spring Boot programado en Java conectado a una base de datos relacional cargada en PostgreSQL.

Fronted(Lo se ve)
