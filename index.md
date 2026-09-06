# Software-Architecture-Laboratory

## Documentación del Proyecto

### Integrantes del grupo

- Jhon Alexander Correa Velasquez
- Holman Steven Herrera Alva 
- Andres julian Forero Gacha 
- Deiby Esteban Gomez Naranjo
- Edwin Mateo Gomez Beltrán 
---

# Calidad y alcance
Requisitos no funcionales:
Los requisitos no funcionales determinan las características de calidad, así como las condiciones bajo las que debe funcionar MotoTaller. Son requisitos que hay que realizar porque la aplicación manejará información de clientes, motocicletas, servicios, ventas, repuestos, usuarios e inventarios.
Requisito	Descripción	Justificación
Seguridad	El sistema debe proteger la información y evitar accesos no autorizados.	MotoTaller manejará información de clientes, ventas, servicios e inventario que debe mantenerse protegida.
Autenticación	Los usuarios deberán ingresar mediante un usuario y contraseña.	Permite identificar a cada usuario y controlar el acceso al sistema.
Roles	El sistema deberá permitir diferentes tipos de usuarios, de acuerdo con sus funciones.	Un administrador puede necesitar más funcionalidades que un empleado del taller.
Permisos	Cada usuario tendrá acceso únicamente a las funciones que correspondan a su rol.	Permite limitar el acceso a información y operaciones que no sean necesarias para cada usuario.
Protección de la información	Los datos almacenados deberán protegerse contra accesos, modificaciones o pérdidas no autorizadas.	Es necesario preservar la confidencialidad y seguridad de la información del taller y sus clientes.
Rendimiento	Las operaciones principales del sistema deberán tener un tiempo de respuesta adecuado.	Un sistema con buena velocidad permite realizar las actividades del taller de manera más eficiente.
Capacidad de usuarios	El sistema deberá permitir que varios usuarios trabajen simultáneamente sin afectar significativamente su funcionamiento.	Diferentes empleados pueden necesitar utilizar el sistema al mismo tiempo.
	
Disponibilidad	El sistema deberá estar disponible durante el horario de funcionamiento del taller.	Los empleados necesitan consultar y registrar información mientras realizan sus actividades.
Escalabilidad	La arquitectura deberá permitir agregar nuevos módulos y funcionalidades en el futuro.	El sistema podrá crecer posteriormente con funciones como reportes, facturación o notificaciones.
Mantenibilidad	El código deberá estar organizado y utilizar una arquitectura modular.	Facilita corregir errores, realizar actualizaciones y agregar nuevas funcionalidades.
Usabilidad	La interfaz deberá ser sencilla, clara e intuitiva.	Los trabajadores del taller deben poder utilizar el sistema fácilmente sin requerir conocimientos avanzados de informática.
Integridad	La información almacenada debe ser consistente, correcta y confiable.	Evita errores como cantidades incorrectas de inventario o información asociada al cliente equivocado.

Alcance del Sistema
El alcance de MotoTaller indica esas funcionalidades que se consideran serán las de la primera versión del sistema y aquéllas que, al menos inicialmente, quedarán excluidas del alcance del sistema. Esto permite concentrar los recursos del proyecto en aquellas funciones básicas e imprescindibles para la gestión de un taller de motocicletas.

Dentro del Proyecto
El primer lanzamiento de MotoTaller permitirá tener las siguientes funcionalidades:
•	Gestión de clientes: poder registrar, consultar y mantener información de los clientes.
•	Gestión de motocicletas: poder registrar motocicletas e identificar sus propietarios.
•	Gestión de servicios: poder registrar y seguir los servicios recibidos de las motocicletas.
•	Ventas: poder registrar y consultar el detalle de las ventas realizadas por el taller.
•	Repuestos: poder registrar y gestionar los repuestos disponibles.
•	Usuarios: poder crear y gestionar usuarios del sistema.
•	Inventario: poder controlar las existencias y movimientos de los repuestos.
•	Base de datos: poder almacenar la información del sistema de forma concreta y ordenada.
•	Sistema web: poder acceder a las funcionalidades mediante una interfaz web.
•	API/Backend: poder procesar la lógica del sistema y la comunicación con la base de datos.

Fuera de la Primera version
Con el fin de mantener un alcance realista, no se considerarán las siguientes funcionalidades para la primera versión:
•	Aplicación móvil nativa
•	Pasarela de pagos.
•	Integraciones bancarias.
•	Inteligencia Artificial avanzada.
•	Integración con proveedores externos.
•	Administración avanzada de múltiples sedes.
Estas funcionalidades podrán ser consideradas en futuras versiones del sistema, dependiendo de las necesidades del negocio o los recursos disponibles.

Justificación del alcance mediante la triple restricción
La definición del alcance se realiza teniendo en cuenta la triple restricción de los proyectos: alcance, tiempo y costo.
Restricción	Aplicación en MotoTaller
Alcance	Se priorizan las funcionalidades principales para la gestión de clientes, motocicletas, servicios, ventas, repuestos, usuarios e inventario.
Tiempo	Se limita la primera versión a las funciones esenciales para poder desarrollar y entregar el sistema dentro del tiempo disponible.
Costo	Se dejan para futuras versiones las funcionalidades que pueden requerir mayores recursos, servicios externos o infraestructura adicional.



La eliminación de funcionalidades tales como una app móvil nativa, pasarelas de pago, integraciones bancarias, inteligencia artificial avanzada, conexión con los proveedores externos; permite bajar la complejidad inicial del proyecto. De esta manera, el equipo puede concentrarse en hacer funcionar adecuadamente las funcionalidades principales del sistema, sin salir de los límites de tiempo y de costo.
Así, el alcance inicial de MotoTaller busca encontrar esos equilibrios entre las necesidades principales del taller y los disponibles para el desarrollo. Las funcionalidades que no se alcance a incluir se podrán incorporar tal como se va haciendo con nuevas versiones del sistema
