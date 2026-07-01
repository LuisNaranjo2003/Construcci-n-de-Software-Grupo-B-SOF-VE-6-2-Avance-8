# BOOKORA_EC

Sistema web de gestión de reservas para peluquerías, barberías y centros de atención, desarrollado con Angular, PHP y MySQL.

# Descripción

BOOKORA_EC es una plataforma web diseñada para optimizar la administración de reservas, servicios y usuarios dentro de negocios de belleza y cuidado personal.

El sistema permite a los clientes realizar reservas de forma rápida y sencilla, mientras que los administradores pueden gestionar servicios, usuarios, horarios y estadísticas desde un panel administrativo moderno e intuitivo.

# Tecnologías Utilizadas

# Frontend
Angular 21
TypeScript
HTML5
CSS3
SweetAlert2
# Backend
PHP 8
Arquitectura MVC
# Base de Datos
MySQL
# Herramientas de Desarrollo
Visual Studio Code
Antigravity
XAMPP
Git
GitHub
MySQL Workbench
# Librerías
jsPDF (Generación de reportes PDF)

# Arquitectura del Proyecto
bookora_ec/
│
├── frontend/
│   ├── src/
│   ├── assets/
│   ├── app/
│   └── environments/
│
├── backend/
│   ├── app/
│   │   ├── controllers/
│   │   ├── models/
│   │   └── core/
│   │
│   ├── routes/
│   ├── public/
│   │   └── uploads/
│   │
│   └── reportes/
│
└── database/

# Roles del Sistema
Administrador

Puede:

Gestionar usuarios.
Gestionar servicios.
Visualizar estadísticas.
Generar reportes PDF.
Administrar reservas.
Eliminar registros.
Supervisar la actividad general del sistema.
Cliente

Puede:

Registrarse.
Iniciar sesión.
Consultar servicios.
Realizar reservas.
Visualizar sus citas.
Cancelar reservas.

# uncionalidades Implementadas
Autenticación
Registro de usuarios.
Inicio de sesión.
Cierre de sesión.
Control de acceso por roles.
Gestión de Servicios
Crear servicios.
Listar servicios.
Eliminar servicios.
Carga de imágenes.
Gestión de Usuarios
Visualización de usuarios.
Eliminación de usuarios.
Gestión de Reservas
Crear reservas.
Consultar reservas.
Cancelar reservas.
Validación de horarios.
Dashboard Administrativo
Total de usuarios.
Total de servicios.
Total de reservas.
Estadísticas generales.
Reportes
Generación de reportes PDF.
Servicio más solicitado.
Cliente más frecuente.
Top de servicios.
Estado de reservas.
Notificaciones
Reservas próximas.
Reservas confirmadas.
Reservas pendientes.

# Base de Datos

Principales tablas:

roles
usuarios
servicios
citas
horarios
bloqueos
notificaciones

# Seguridad
Validación de formularios.
Protección de rutas.
Control de acceso por roles.
Restricción de acceso a paneles administrativos.
Gestión segura de sesiones.

# nstalación
1. Clonar repositorio
git clone https://github.com/LuisNaranjo2003/bookora_ec.git
2. Configurar Base de Datos

Crear la base de datos:

CREATE DATABASE bookora;

Importar el script SQL correspondiente.

3. Configurar Backend

Ubicar el proyecto dentro de:

xampp/htdocs/bookora_ec

Iniciar:

Apache
MySQL

desde XAMPP.

4. Ejecutar Frontend
npm install
ng serve

Abrir:

http://localhost:4200

# Mejoras Futuras
Estadísticas gráficas.
Reportes avanzados.
Exportación a Excel.
Sistema de pagos.
Notificaciones por correo electrónico.
Aplicación móvil.
Reservas en tiempo real.

# Autor

Proyecto desarrollado por:

Grupo B Construcción de Software SOF-VE-6-2 CI 2026 2027

Universidad de Guayaquil

Carrera de Software

# Licencia

Proyecto académico desarrollado con fines educativos.
