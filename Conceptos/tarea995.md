# Tarea995

## CIA Triad

Este es un concepto de ciberseguridad, es una guía para la seguridad de la información. Las siglas indican 
Confidentiality,  Integrity and Availability. En español indican confidencialidad, integridad y disponibilidad de los datos. La confidencialidad indica que los datos no pueden ser accedidos por usuarios no autorizados, la integridad es que los datos son confiables, completos y no han sido modificados por usuarios no autorizados, por último la disponibilidad es que se pueda acceder cuando se requiere.

![CIA triad](/Conceptos/cia_triangle.png)

## Usability Triangle

Este triángulo indica que cuando la seguridad del sistema aumenta la funcionalidad y la usabilidad del sistema baja. Las organizaciones deben de balancear entre estas tres cualidades.

* Funcionalidad: Las cualidades que tiene el sistema
* Usabilidad: qué tan fácil el sistema se puede usar por el usuario.
* Seguridad: Las restricciones que se tienen para acceder a diferentes partes del sistema.

![Usability Triangle](/Conceptos/triangle_usabilit.png)

## Multi Factor Authentication
Es un proceso de registro que requiere que el usuario se autentifique de otras formas aparte de la contraseña. Puede ser un código a su dispositivo móvil, a su correo electrónico o una llamada. Huella dactilar es otro ejemplo.La autenticación multifactor actúa como una capa adicional de seguridad para evitar que usuarios no autorizados accedan a dichas cuentas, incluso cuando se ha robado la contraseña
Proceso Autenticación multifactor 

*Registro
	*Se registra el usuario y contraseña adicionalmente se vinculan los demás elementos que estarán asociados a la cuenta. (dirección de correo, número de celular).

*Autenticación 
	*Se solicita el usuario y contraseña, y se solicita la autenticación multifactor. Se espera la respuesta del otro dispositivos.Si coincide se conecta con los demás elementos.

*Reacción
	*El usuario completa el proceso.

### Métodos de Autenticación 

*Factor de Conocimiento*: Revelación de identidad que nadie conoce. Pregunta secreta, acceso pin. Solo es seguro mientras nadie más conozca esta información

*Factor de Posesión*: Se identifican mediante algo que solo ellos tienen. Celular, token, correo electrónico.

*Factor de inherencia*: utilizan información inherente del usuario.  huellas dactilares, Reconocimiento facial, etc.

## Riesgo 
Es la posibilidad de que ocurra un evento indeseable que ponga en peligro la confidencialidad, la integridad o la disponibilidad de los sistemas y datos

## Vulnerabilidad

Son errores en la seguridad de un sistema que pueden ser explotados por atacantes con intenciones maliciosas. Estas vulnerabilidades pueden dar acceso no autorizado a cuentas, bases de datos o permitir ataques de ingeniería social y denegación de servicio.
Ejemplos:

* Desbordamiento de buffer.
* Cross-Site scripting
* Inyección SQL
* Denegación de Servicio

## Amenaza 
Son ataques informáticos que buscan obtener información confidencial, bloquear el acceso a los sistemas, difundir información confidencial, bloquear acceso a los sistemas.
* Phishing 
* Ransomware
* MAlware
* Spam

![Tipos Malware](/Conceptos/tipos_malware.png)
