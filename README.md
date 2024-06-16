# Sistema de Gestion de Proyectos de la Empresa FuturaSoft

[Visítanos en www.FuturaSoft.net](www.futurasoft.net)

## Descripción
El **Sistema de Gestión de Proyectos de FuturaSoft** es una aplicación diseñada para ayudar a las empresas a planificar, ejecutar y supervisar sus proyectos de manera eficiente. Proporciona herramientas para la gestión de tareas, asignación de recursos, seguimiento del progreso y colaboración del equipo.

## Características
- **Gestión de Tareas**: Creación, asignación y seguimiento de tareas.
- **Planificación de Proyectos**: Herramientas para definir objetivos, plazos y hitos del proyecto.
- **Asignación de Recursos**: Gestión eficiente de los recursos del proyecto.
- **Colaboración del Equipo**: Comunicación y colaboración en tiempo real entre los miembros del equipo.
- **Reportes y Análisis**: Generación de informes detallados sobre el progreso y el rendimiento del proyecto.

## Tecnologías Utilizadas
- **Backend**: Node.js, Express
- **Frontend**: React.js
- **Base de Datos**: MongoDB
- **Autenticación**: JWT (JSON Web Tokens)
- **Control de Versiones**: Git

## Instalación

### Prerrequisitos
- Node.js (v14 o superior)
- npm (v6 o superior)
- MongoDB (v4 o superior)

### Pasos para la Instalación
1. **Clonar el repositorio**:
    ```sh
    git clone https://github.com/FuturaSoft/project-management-system.git
    cd project-management-system
    ```

2. **Instalar dependencias**:
    ```sh
    npm install
    ```

3. **Configurar las variables de entorno**:
   Crear un archivo `.env` en la raíz del proyecto y añadir las siguientes variables:
    ```env
    PORT=3000
    MONGODB_URI=mongodb://localhost:27017/futurapm
    JWT_SECRET=your_secret_key
    ```

4. **Iniciar el servidor**:
    ```sh
    npm start
    ```

5. **Acceder a la aplicación**:
   Abre tu navegador web y navega a `http://localhost:3000`.

## Uso
### Crear un Proyecto
1. Navega a la pestaña "Proyectos" y haz clic en "Nuevo Proyecto".
2. Introduce los detalles del proyecto y haz clic en "Guardar".

### Asignar Tareas
1. Selecciona un proyecto existente.
2. Navega a la pestaña "Tareas" y haz clic en "Nueva Tarea".
3. Introduce los detalles de la tarea y asigna a un miembro del equipo.
4. Haz clic en "Guardar".

### Seguimiento del Progreso
1. En la vista del proyecto, navega a la pestaña "Progreso".
2. Visualiza el estado actual de las tareas y el progreso del proyecto en general.

### Generación de Informes
1. Navega a la pestaña "Informes".
2. Selecciona el tipo de informe que deseas generar.
3. Haz clic en "Generar Informe" y descarga el reporte.

## Contribución
¡Contribuciones son bienvenidas! Para contribuir, sigue estos pasos:
1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir nueva funcionalidad'`).
4. Sube tus cambios (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para obtener más detalles.

## Contacto
Para cualquier consulta o sugerencia, por favor contacta con el equipo de FuturaSoft en [contacto@futurasoft.com](mailto:info@futurasoft.net).

---

¡Gracias por usar el Sistema de Gestión de Proyectos de FuturaSoft!

