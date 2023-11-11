# CRUDluis
 examen final
Claro, aquí tienes el texto con algunas modificaciones:

**Manual de Usuario - Sistema de Gestión de Estudiantes 

Este manual ofrece una guía detallada sobre el uso del Sistema de Gestión de Estudiantes, diseñado para realizar operaciones básicas de un CRUD (Crear, Leer, Actualizar, Eliminar) en estudiantes almacenados en una base de datos en MySQL Workbench. A continuación, se detallan las funciones principales y cómo utilizarlas.

**0. Inicio de Sesión:**
Para utilizar el programa, debes iniciar sesión con un usuario y contraseña previamente creados.

**1. Lista de Estudiantes:**
Al abrir la aplicación, se mostrará una lista de estudiantes almacenados en la base de datos, incluyendo información como nombre, apellido y correo electrónico.

**2. Agregar un Estudiante:**
Para añadir un nuevo estudiante, sigue estos pasos:

- Haz clic en el enlace "Agregar".
- Se abrirá un formulario con campos para nombre, descripción, unidad y precio.
- Ingresa la información del nuevo estudiante.
- Haz clic en el botón "Agregar" para guardar los cambios.

**3. Modificar un Estudiante:**
Para modificar un estudiante existente, sigue estos pasos:

- Busca el estudiante en la lista.
- Haz clic en el enlace "Actualizar" junto al estudiante deseado.
- Se abrirá un formulario prellenado con la información actual del estudiante.
- Modifica los campos deseados.
- Haz clic en el botón "Guardar" para aplicar los cambios.

**4. Eliminar un Estudiante:**
Para eliminar un estudiante, sigue estos pasos:

- Busca el estudiante en la lista.
- Haz clic en el enlace "Eliminar" junto al estudiante deseado.
- Confirma la eliminación cuando se te solicite.

**5. Empleados:**
En la página, hay una sección llamada "Empleados" donde puedes agregar un empleado con campos para Nombre, Correo y Contraseña.

**6. Actualizar información de Empleados:**
Los usuarios pueden modificar la información de los empleados según sea necesario y también eliminar usuarios.

**User Manual - Student Management System // English**

Este manual proporciona una guía detallada sobre cómo utilizar el Sistema de Gestión de Estudiantes, diseñado para realizar operaciones básicas de CRUD en estudiantes almacenados en una base de datos de MySQL Workbench. A continuación, se describen las funciones principales y cómo utilizarlas.

**0. Login:**
Para utilizar el programa, debes iniciar sesión con un nombre de usuario y contraseña previamente creados.

**1. Lista de Estudiantes:**
Al abrir la aplicación, se mostrará una lista de estudiantes actualmente almacenados en la base de datos. La lista incluirá información como nombre, apellido y correo electrónico.

**2. Add a Student:**
Para añadir un nuevo estudiante, sigue estos pasos:

- Haz clic en el enlace "Add".
- Se abrirá un formulario con campos para nombre, descripción, unidad y precio.
- Ingresa la información del nuevo estudiante.
- Haz clic en el botón "Add" para guardar el nuevo estudiante.

**3. Modify a Student:**
Para modificar un estudiante existente, sigue estos pasos:

- Encuentra el estudiante en la lista.
- Haz clic en el enlace "Update" junto al estudiante deseado.
- Se abrirá un formulario prellenado con la información actual del estudiante.
- Modifica los campos que desees actualizar.
- Haz clic en el botón "Save" para aplicar los cambios.

**4. Delete a Student:**
Para eliminar un estudiante existente, sigue estos pasos:

- Encuentra el estudiante en la lista.
- Haz clic en el enlace "Delete" junto al estudiante deseado.
- Confirma la eliminación cuando se te solicite.

**5. Employees:**
En la página, hay una sección llamada "Employees" donde puedes agregar un empleado con campos para Name, Email y Password.

**6. Update Employee Information:**
La persona que utiliza el programa puede modificar la información del usuario si es necesario y también eliminar usuarios.

**Manual técnico // español**

**Introducción:**
El Sistema de Gestión de Estudiantes es una aplicación de software diseñada para realizar operaciones CRUD en datos de estudiantes almacenados en una base de datos de MySQL Workbench. Este manual técnico proporciona información detallada sobre la arquitectura, componentes y funcionalidad del sistema.

**Arquitectura del Sistema:**

**2.1 Frontend:**
El frontend de la aplicación se construye utilizando tecnologías web, incluyendo HTML, CSS y JavaScript para crear una interfaz fácil de usar. Los usuarios interactúan con el sistema a través de páginas web que facilitan la navegación sin problemas.

**2.2 Backend:**
El backend se implementa utilizando un lenguaje del lado del servidor, como Python o Node.js, y maneja las solicitudes de los usuarios, procesa datos e interactúa con la base de datos mediante solicitudes HTTP.

**2.3 Base de Datos:**
La base de datos de MySQL Workbench almacena información de estudiantes y empleados, estructurada eficientemente para admitir operaciones CRUD. El esquema incluye tablas para estudiantes y empleados, capturando información relevante como nombres, direcciones de correo electrónico y contraseñas.

**Funcionalidad del Sistema:**

**3.1 Autenticación de Usuarios (Login):**
Los usuarios deben iniciar sesión con un nombre de usuario y contraseña preexistentes para acceder al sistema, garantizando la seguridad de la información del usuario.

**3.2 Lista de Estudiantes:**
Al iniciar sesión, el sistema muestra una lista de estudiantes recuperada de la base de datos, incluyendo detalles como nombres, apellidos y direcciones de correo electrónico.

**3.3 Agregar un Estudiante:**
Para añadir un nuevo estudiante, el usuario hace clic en el enlace "Agregar", lo que abre un formulario con campos para nombre, descripción, unidad y precio. Al ingresar la información, hacer clic en el botón "Agregar" guarda al nuevo estudiante en la base de datos.

**3.4 Modificar un Estudiante:**
Los usuarios pueden modificar la información de los estudiantes existentes seleccionando el enlace "Actualizar" junto al estudiante deseado. Esto abre un formulario prellenado con la información actual, permitiendo a los usuarios realizar cambios. Hacer clic en el botón "Guardar" aplica las actualizaciones a la base de datos.

**3.5 Eliminar un Estudiante:**
Para eliminar un estudiante, los usuarios hacen clic en el enlace "Eliminar" junto al estudiante deseado, confirmando la eliminación cuando se les solicita. El sistema garantiza la integridad de los datos durante este proceso.

**3.6 Gestión de Empleados:**
El sistema incluye una sección de empleados donde los usuarios pueden agregar empleados con campos para nombre, correo electrónico y contraseña. Además, los usuarios pueden actualizar y eliminar información de emple

ados según sea necesario.

**Consideraciones de Seguridad:**
El sistema incorpora medidas de autenticación seguras para proteger las cuentas de usuario y la información sensible. Además, se implementa validación y saneamiento de datos para prevenir vulnerabilidades de seguridad comunes como la inyección de SQL.

**Mejoras Futuras:**
Posibles mejoras futuras pueden incluir la implementación de características adicionales, una interfaz de usuario mejorada e integración con otros sistemas para una funcionalidad mejorada.

**Conclusión:**
Este manual técnico proporciona una visión general de la arquitectura, funcionalidad y consideraciones de seguridad del Sistema de Gestión de Estudiantes. Tanto usuarios como desarrolladores pueden utilizar este documento como referencia para comprender y mantener el sistema.
