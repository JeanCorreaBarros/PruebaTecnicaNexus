# Prueba Técnica para Frontend Developer en React.js con Vite y Tailwind CSS (CRUD y Autenticación)

## Objetivo:
Desarrollar una aplicación web tipo CRUD con funcionalidad de inicio de sesión utilizando React.js con Vite como herramienta de construcción y Tailwind CSS para estilizar la interfaz de usuario. La aplicación debe consumir un conjunto de endpoints proporcionados y mostrar los datos de manera adecuada en la interfaz de usuario, permitiendo al usuario realizar operaciones de Crear, Leer, Actualizar y Eliminar sobre los elementos, además de iniciar sesión.

## Requerimientos:

### Configuración del Proyecto:
- Inicializar un nuevo proyecto de React.js utilizando Vite.
- Configurar Tailwind CSS para el proyecto.
- Configurar Axios o Fetch para realizar solicitudes HTTP a los endpoints proporcionados.

### Interfaz de Usuario:
- Crear una página de inicio de sesión que permita al usuario ingresar sus credenciales.
- Crear una página principal que muestre una lista de elementos obtenidos del endpoint una vez que el usuario haya iniciado sesión.
- Cada elemento de la lista debe mostrar al menos dos propiedades del objeto obtenido del endpoint.
- Utilizar Tailwind CSS para estilizar la interfaz de usuario de manera atractiva y responsive.

### Consumo de Endpoints:
- Realizar una solicitud HTTP POST al endpoint de inicio de sesión para autenticar al usuario.
- Realizar una solicitud HTTP GET al endpoint CRUD para obtener los datos una vez que el usuario haya iniciado sesión.
- Realizar solicitudes HTTP CRUD (POST, GET, PUT, DELETE) a los endpoints CRUD para realizar operaciones sobre los elementos de la aplicación.
- Manejar cualquier error que pueda ocurrir durante las solicitudes.
- Mostrar una indicación de carga mientras se obtienen los datos del servidor.

### Operaciones CRUD:
- Implementar operaciones de Crear, Leer, Actualizar y Eliminar sobre los elementos obtenidos de los endpoints CRUD.
- Permitir al usuario agregar nuevos elementos a la lista.
- Permitir al usuario actualizar y eliminar elementos existentes de la lista.

### Funcionalidades Adicionales (Opcionales):
- Implementar funcionalidad de búsqueda para filtrar los elementos mostrados en la lista.
- Agregar paginación para mostrar los resultados de forma paginada.

## Instrucciones:
1. Configura tu entorno de desarrollo local según las instrucciones proporcionadas.
2. Desarrolla la aplicación cumpliendo con los requerimientos especificados.
3. Realiza pruebas exhaustivas para garantizar el correcto funcionamiento de la aplicación.
4. Documenta cualquier decisión de diseño o implementación que consideres relevante.
5. Una vez completada la prueba, notifica al reclutador y proporciona cualquier instrucción adicional que consideres necesaria, incluyendo el archivo de Postman con los endpoints a consumir.

## Evaluación:
- Se evaluará la calidad del código, el cumplimiento de los requisitos, el diseño de la interfaz y la implementación de las operaciones CRUD y de inicio de sesión según los criterios especificados en la prueba técnica, así como la correcta utilización de los endpoints proporcionados en el archivo de Postman.
