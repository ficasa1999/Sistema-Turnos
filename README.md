# Sistema de Citas y Turnos Universitarios (UniTurnos)

Proyecto desarrollado para la asignatura de Ingeniería de Software I. Este sistema permite gestionar turnos y citas académicas para evitar filas en la universidad.

## Objetivo del Proyecto
Optimizar y automatizar el proceso de asignación y seguimiento de citas académicas y turnos de atención para la comunidad universitaria, reduciendo tiempos de espera y organizando la atención presencial y virtual.

## Problema que Resuelve
Actualmente, la gestión manual o desorganizada de filas y solicitudes genera demoras, saturación en las oficinas de atención estudiantil y falta de visibilidad en el estado de los trámites por parte de los estudiantes.

## Funcionalidades Principales
- **Registro y Autenticación:** Acceso de estudiantes y personal administrativo.
- **Gestión de Citas:** Programación, reprogramación y cancelación de citas académicas.
- **Control de Turnos en Tiempo Real:** Visualización y llamada de turnos consecutivos.
- **Panel de Administración:** Reportes y monitoreo del flujo de atención.

## Arquitectura Seleccionada y Herramientas
- **Arquitectura:** Arquitectura en Capas / Cliente-Servidor.
- **Herramientas de Diseño y Desarrollo:** Visual Paradigm Online (Modelado UML), Visual Studio (Desarrollo), GitHub Projects (Gestión del proyecto) y Git/GitHub (Control de versiones).

## Organización Frontend / Backend

El sistema se encuentra estructurado bajo una arquitectura modular y desacoplada, separando la interfaz de usuario de la lógica de negocio y gestión de datos:

* **Frontend (Capa de Presentación):** Es la interfaz con la que interactúan directamente los usuarios (estudiantes y personal administrativo). Se encarga de capturar las solicitudes, validar los datos de entrada en tiempo real y renderizar visualmente los turnos y la información del sistema.
* **Backend (Capa de Lógica de Negocio):** Es el motor central del sistema. Se encarga de procesar las peticiones recibidas, aplicar las reglas de negocio (como el ordenamiento y asignación de turnos), gestionar las validaciones y administrar la persistencia de los datos.
* **Comunicación:** La interacción entre ambas capas se realiza mediante peticiones y respuestas HTTP estructuradas (siguiendo principios de API REST o servicios internos), permitiendo un flujo de datos sincronizado, seguro y eficiente para el funcionamiento del proyecto.

## Cómo ejecutar
1. Abrir el proyecto en Visual Studio.
2. Compilar y ejecutar el archivo principal (Program.cs).
