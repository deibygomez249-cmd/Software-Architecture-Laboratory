# Software-Architecture-Laboratory

## Documentación del Proyecto

### Integrantes del grupo

- Jhon Alexander Correa Velasquez
- Holman Steven Herrera Alva 
- Andres julian Forero Gacha 
- Deiby Esteban Gomez Naranjo
- Edwin Mateo Gomez Beltrán 
---

# 1. Antecedentes

En esta sección se presentan las aplicaciones similares investigadas por los integrantes del grupo. Se realiza una comparación teniendo en cuenta aspectos como funcionalidades, módulos, costos, características principales y otros elementos relevantes para el proyecto.

---

# 2. Requisitos Funcionales

Los requisitos funcionales describen las principales funciones que debe realizar el sistema.

En esta sección se presenta la descomposición funcional del sistema mediante un árbol de requisitos funcionales, con un máximo de cuatro niveles.

Los requisitos funcionales serán definidos de acuerdo con las necesidades identificadas para la aplicación seleccionada.

---

# 3. Requisitos No Funcionales

## Aplicación #4: MotoTaller

MotoTaller es una solución orientada a la gestión de talleres de motocicletas. El sistema debe cumplir diferentes características de calidad para garantizar un funcionamiento seguro, confiable, eficiente y fácil de utilizar.

### Requisitos no funcionales

| Requisito | Descripción | Justificación |
|---|---|---|
| **Seguridad** | El sistema debe proteger la información contra accesos no autorizados. | Se manejará información de clientes, motocicletas, servicios, ventas e inventario. |
| **Autenticación** | Los usuarios deben ingresar mediante usuario y contraseña. | Permite identificar y autenticar a cada usuario del sistema. |
| **Roles** | El sistema debe permitir diferentes tipos de usuarios. | Los administradores y empleados pueden tener diferentes responsabilidades. |
| **Permisos** | Cada usuario debe acceder únicamente a las funciones autorizadas para su rol. | Evita operaciones y accesos no autorizados. |
| **Protección de la información** | La información almacenada debe protegerse contra accesos, modificaciones o pérdidas no autorizadas. | Permite proteger la información de los clientes y del negocio. |
| **Rendimiento** | El sistema debe ofrecer tiempos de respuesta adecuados en sus operaciones principales. | Permite que los empleados realicen sus actividades de manera eficiente. |
| **Capacidad de usuarios** | El sistema debe permitir que varios usuarios trabajen simultáneamente. | Diferentes empleados pueden necesitar utilizar el sistema al mismo tiempo. |
| **Disponibilidad** | El sistema debe estar disponible durante el horario de funcionamiento del taller. | Los empleados necesitan acceder a la información durante sus actividades. |
| **Escalabilidad** | La arquitectura debe permitir agregar nuevos módulos y funcionalidades. | El sistema puede crecer de acuerdo con las necesidades futuras del taller. |
| **Mantenibilidad** | El código debe estar organizado y utilizar una arquitectura modular. | Facilita corregir errores, realizar mantenimiento y agregar funcionalidades. |
| **Usabilidad** | La interfaz debe ser sencilla, clara e intuitiva. | Los empleados deben poder utilizar el sistema fácilmente. |
| **Integridad** | La información debe mantenerse correcta, consistente y confiable. | Evita errores en datos de clientes, servicios, ventas e inventario. |

### Justificación de los requisitos no funcionales

Los requisitos no funcionales seleccionados son importantes porque permiten garantizar que MotoTaller no solamente cumpla con sus funciones principales, sino que también sea seguro, confiable y fácil de utilizar.

La seguridad, autenticación, roles, permisos y protección de la información permiten controlar el acceso al sistema y proteger los datos de los clientes y del taller.

El rendimiento, la capacidad de usuarios y la disponibilidad permiten que los empleados puedan utilizar el sistema de manera eficiente durante las actividades del taller.

Por otra parte, la escalabilidad y la mantenibilidad permiten que el sistema pueda crecer y actualizarse en el futuro sin necesidad de reconstruirlo completamente.

Finalmente, la usabilidad facilita la interacción de los usuarios con el sistema, mientras que la integridad permite mantener información correcta y consistente.

---

# 4. Alcance del Sistema

## Aplicación #4: MotoTaller

El alcance de MotoTaller establece las funcionalidades que serán incluidas en la primera versión del sistema y aquellas que quedarán para futuras versiones.

### Dentro del proyecto

La primera versión de MotoTaller incluirá:

- **Gestión de clientes:** registro, consulta y actualización de información de los clientes.
- **Gestión de motocicletas:** registro de motocicletas y asociación con sus propietarios.
- **Gestión de servicios:** registro y seguimiento de los servicios realizados.
- **Ventas:** registro y consulta de las ventas realizadas por el taller.
- **Repuestos:** registro y administración de los repuestos disponibles.
- **Usuarios:** creación y administración de los usuarios del sistema.
- **Inventario:** control de existencias y movimientos de los repuestos.
- **Base de datos:** almacenamiento organizado de la información.
- **Sistema web:** acceso al sistema mediante una interfaz web.
- **API/Backend:** procesamiento de la lógica del sistema y comunicación con la base de datos.

### Fuera de la primera versión

Las siguientes funcionalidades no serán incluidas inicialmente:

- Aplicación móvil nativa.
- Pasarela de pagos.
- Integraciones bancarias.
- Inteligencia Artificial avanzada.
- Integración con proveedores externos.
- Administración avanzada de múltiples sedes.

Estas funcionalidades podrán ser consideradas en futuras versiones dependiendo de las necesidades del negocio y de los recursos disponibles.

---

## Triple Restricción

El alcance de MotoTaller se establece teniendo en cuenta la triple restricción de los proyectos: **alcance, tiempo y costo**.

| Restricción | Aplicación en MotoTaller |
|---|---|
| **Alcance** | Se priorizan las funciones principales para gestionar clientes, motocicletas, servicios, ventas, repuestos, usuarios e inventario. |
| **Tiempo** | La primera versión se limita a las funciones esenciales para poder desarrollar el sistema dentro del tiempo disponible. |
| **Costo** | Las funcionalidades más complejas o que requieren servicios externos se dejan para futuras versiones. |

### Justificación del alcance

El alcance de MotoTaller se limita a las funcionalidades esenciales para mantener un proyecto realista y posible de desarrollar dentro del tiempo y los recursos disponibles.

Funcionalidades como una aplicación móvil nativa, pasarelas de pago, integraciones bancarias, inteligencia artificial avanzada y conexiones con proveedores externos aumentan la complejidad, el tiempo de desarrollo y los posibles costos del proyecto.

Por esta razón, estas funcionalidades serán consideradas para futuras versiones, mientras que la primera versión se concentrará en las necesidades principales del taller.

---

# 5. Tecnologías Seleccionadas

En esta sección se presentan las tecnologías seleccionadas por el grupo para el desarrollo del proyecto.

Se deben incluir las tecnologías utilizadas para:

- Desarrollo del sistema.
- Backend.
- Frontend.
- Base de datos.
- Arquitectura.
- Control de versiones.
- Despliegue.

---

# 6. Referencias

En esta sección se incluyen las fuentes consultadas durante el desarrollo del proyecto, utilizando las normas APA.

Se deben incluir:

- Fuentes utilizadas para investigar las aplicaciones similares.
- Documentación oficial de las tecnologías utilizadas.
- Fuentes utilizadas para definir los requisitos.
- Otras fuentes académicas o confiables consultadas.
