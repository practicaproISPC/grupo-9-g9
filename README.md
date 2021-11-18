






























Especificación de requisitos de software

Proyecto:  















		
2021
 
Instrucciones para el uso de este formato

Este formato es una plantilla tipo para documentos de requisitos del software.

Está basado y es conforme con el estándar IEEE Std 830-1998.

Los textos en color azul son indicaciones que deben eliminarse y, en su caso, sustituirse por los contenidos descritos en cada apartado.































. 
Ficha del documento


Fecha	Revisión	Autor	Verificado dep. Calidad.
2021		Pablo Alejandro Bajar
Luciano Cancinos
Gustavo Emilio Lima	








 
Contenido
FICHA DEL DOCUMENTO	3
CONTENIDO	4
1	INTRODUCCIÓN	6
1.1	Propósito	6
1.2	Alcance	6
1.3	Personal involucrado	6
1.4	Definiciones, acrónimos y abreviaturas	7
1.5	Referencias	7
1.6	Resumen	7
2	DESCRIPCIÓN GENERAL	7
2.1	Perspectiva del producto	7
2.3	Características de los usuarios	8
2.4	Restricciones	9
3	REQUISITOS ESPECÍFICOS	9
3.2	Product Backlog	17
3.2.1	Product Backlog	17
3.3	Sprints	19
3.3.1	Sprint 1	19
3.3.2	Spint 2	20


 
1	Introducción

	Este documento es una Especificación de Requisitos Software (ERS) para el Sistema de información para la gestión de procesos y control de inventarios. Esta especificación se ha estructurado basándose en las directrices dadas por el estándar IEEE Práctica Recomendada para Especificaciones de Requisitos Software ANSI/IEEE 830, 1998.

1.1	Propósito

	El presente documento tiene como propósito definir las especificaciones funcionales, para el desarrollo de un sistema de información web que permitirá  gestionar procesos educativos y será utilizado por docentes y  alumnos.

1.2	Alcance

Esta especificación de requisitos está dirigida al usuario del sistema para continuar con el desarrollo de la aplicación web y para profundizar en la automatización de Aula virtual la cual tiene por objeto  principal gestionar los distintos procesos educativos (actividades propuestas, actividades desarrolladas) y administrativos (informes, notificaciones, seguimiento y calificaciones)

1.3	Personal involucrado

Nombre	Pablo Alejandro Bajar
Rol	Análisis y Desarrollador
Categoría Profesional	Estudiante
Responsabilidad	Desarrollador  Base datos SQL
Información de contacto	pabloaleja.bajar@gmail.com 

Nombre	Luciano Cancinos
Rol	Análisis Desarrollador
Categoría Profesional	Estudiante
Responsabilidad	Desarrollador  Base datos SQL
Información de contacto	lucianocancios99@gmail.com

Nombre	Gustavo Emilio Lima
Rol	Análisis y Desarrollador
Categoría Profesional	Estudiante
Responsabilidad	Desarrollador Base datos SQL
Información de contacto	gutu3@hotmail.com






1.4	Definiciones, acrónimos y abreviaturas

Nombre	Descripción
Usuario	Persona que usará el sistema para gestionar procesos
SIS-I	Sistema de Información Web para la Gestión de Procesos Administrativos y Académicos
ERS	Especificación de Requisitos Software
RF	Requerimiento Funcional
RNF	Requerimiento No Funcional
FTP	Protocolo de Transferencia de Archivos
SQL	Bases de datos SQL 

1.5	Referencias

Titulo del Documento	Referencia
Standard IEEE 830 - 1998	IEEE 

1.6	Resumen

Este documento consta de  secciones. En la primera sección se realiza una introducción al mismo y se proporciona una visión general de la especificación del sistema Aula virtual

En la segunda sección del documento se realiza una descripción general del sistema con el fin de conocer las principales funciones que éste debe realizar, los datos asociados y los factores, restricciones supuesto y dependencias que afectan al desarrollo sin entrar en extensos detalles.

Por último, la tercer sección del documento es en la que se definen detalladamente los requisitos que debe satisfacer el sistema 

2	Descripción general

2.1	Perspectiva del producto
El sistema Aula virtual está enfocado a cubrir los requerimientos no alcanzados en el área educación no presencial Por lo que se encargara de realizar las siguientes funciones  que solo podrán tener acceso usuarios habilitados: Alumnos realizar actividades propuestas por los docentes. Docentes altas, bajas y modificaciones de alumnos, altas bajas y modificaciones de actividades, calificaciones, informes de progreso, notificaciones a Padres y alumnos, mediante un registro con inicio y cierre de sesión será un producto diseñado para trabajar en entornos WEB, lo que permitirá su fácil utilización de forma rápida y eficaz.



2.2	Características de los usuarios
Tipo de usuario	 Administrador - Docente
Formación	Manejo de herramientas informáticas
Actividades	Control y manejo del sistema en general



Tipo de usuario	Visitante - Alumno
Formación	Manejo de entornos web
Actividades	Observar y completar las actividades propuestas por el docente

.
2.3	Restricciones
•	La interfaz está pensada para ser usada con acceso a internet
•	Lenguajes y tecnologías en uso: HTML, CSS Bootstrap, js, Bases SQL
•	El sistema se diseñara según modelo cliente/servidor
•	El sistema deberá tener un diseño e implementación sencilla, independiente de la plataforma o del lenguaje de programación.



3	Requisitos específicos


Product Backlog


US #2 DEFINIR DISEÑO
Crear un diseño optimo y minimalista para layout

US #3 DISEÑO PÁGINA DE INICIO
Crear un diseño optimo y minimalista para layout

US #4 ALTA DE ALUMNOS
Como Administrador quiero habilitar el alta de alumnos para el ingreso a la plataforma de estudios


US #5 ALTA DOCENTES


US #6 DISEÑO VISTA ALUMNOS

Como Administrador quiero dar diseño/vista clara para que el alumno encuentre las actividades a desarrollar

US #7 DISEÑO VISTA DOCENTE
Como Administrador quiero dar diseño/vista clara para que el docente de altas de actividades para que el alumno pueda desarrolladas

US #8 BASE DE DATOS
Como Administrador quiero tener el registro de actividades de alumnos y docentes para que se puedan elaborar informes seguimiento y desarrollo actividades

US #9 CALENDARIO
Como Administrador quiero elaborar un calendario para que el alumno conozca próximas actividades o fechas de presentación de actividades

US #10 INFORME DE PROGRESO CUATRIMESTRAL
Como Administrador quiero generar un informe para que el alumno conozca las calificaciones de las asignaturas del cuatrimestre

US #11 NOTIFICIACIÓN ALUMNO

US #12 NOTIFICACIÓN DOCENTE
Como Administrador quiero notificar al docente para que pueda hacer el seguimiento de sus alumnos

US #13 ALERTA ALUMNOS
Como Administrador quiero alertar al alumno de actividades nuevas o pendientes de entrega para que pueda cumplir con las actividades propuestas por el docente


US #14 ALERTA DOCENTE
Como Administrador quiero enviar alerta de falta de actividad de alumno(s) para que el docente se ponga en contacto con el alumno, padre o tutor


US #15 SEGUIMIENTO PADRE O TUTOR


US #16 INFORME FINAL

Crear un diseño optimo y minimalista para layout



US #18 DISEÑO - PALETA DE COLORES
Elegir paleta de colores a utilizar en el aula virtual (vista usuario).

Tener en cuenta a los usuarios con daltonismo a la hora de la elección.


US #19 DISEÑO RESPONSIVE

US #20 LAYOUT - LOGIN DE USUARIO

Header con logo y login

Main con formulario para ingresar usuario y contraseña. Campo para recuperar contraseña y/o registrarme.

Footer con copyright


US # 21 VALIDACIONES - LOGIN DE USUARIO
Como Usuario quiero ingresar a la plataforma con mi documento de identidad (DNI) y una contraseña segura y personal


US #22 VALIDACIONES - LOGIN DE USUARIO
Como usuario quiero que en caso de no tener una cuenta que me redirija a un formulario para poder registrarme


US #23 VALIDACIONES - LOGIN DE USUARIO
Como usuario quiero en caso de olvidarme la contraseña poder generar una nueva enviando al correo registrado un mail con la nueva contraseña o formulario en la cual pueda generar una nueva

US #24 VALICACIONES - REGISTRO USUARIO

US #25 LAYOUT - REGISTRO DE USUARIO

US #25 LAYOUT – CONTACTO
Crear un layout para contacto















Sprints.

N° de sprint	01
Sprint Backlog	



Responsabilidades 	







Calendario	




Inconvenientes: Abandono de un integrante del equipo (Núñez, Vanina Eliana)
	


N° de sprint	02
Sprint Backlog	



Responsabilidades 	







Calendario	




Inconvenientes:
	



















N° de sprint	03
Sprint Backlog	



Responsabilidades 	







Calendario	




Inconvenientes:         Falta de conocimientos en de  en la conexión entre el diseño web y la  base de datos (se presentan 2 opciones de SQL 8Microsoft y MySQL)
	
