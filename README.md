<meta property="og:title" content="course-online" />
<meta property="og:description" content="Course Online" />
<meta property="og:image" content="https://www.kopen.es/wp-content/uploads/2022/03/104_17_03_ANALISIS-DE-REQUISITOS.jpg" />
<meta property="og:url" content="https://github.com/ing-reyes/course-online" />

# 📌 Requerimientos del Sistema de Cursos Online

## 1️⃣ Requerimientos Funcionales ⚙️

### 👥 Gestión de Usuarios
- Registro e inicio de sesión con **email y contraseña** 🔑.
- Roles de usuario: **Administrador, Docente, Estudiante** 🎭.
- Recuperación de contraseña vía correo electrónico 📧.
- Autenticación mediante **JWT** 🔐.

### 📚 Gestión de Cursos
- Creación, edición y eliminación de cursos por docentes 👨‍🏫.
- Organización de cursos en módulos y lecciones 🎓.
- Acceso restringido solo a estudiantes inscritos 🔒.

### 🎬 Gestión de Contenido Multimedia
- Subida y gestión de videos, documentos y materiales adicionales 📂.
- Reproducción segura de videos en la plataforma 📺.

### 💰 Gestión de Pagos
- Integración con **PayPal** y **tarjetas de crédito/débito** 💳.
- Confirmación automática de pagos exitosos ✅.
- Generación de facturas y comprobantes 🧾.

### 📊 Gestión del Progreso del Estudiante
- Registro del avance en cada lección 📝.
- Emisión de certificados al finalizar un curso 📜.

### ⭐ Reseñas y Calificaciones
- Permitir a los estudiantes calificar y comentar sobre los cursos 📢.
- Moderación de comentarios por parte del administrador ⚖️.

## 2️⃣ Requerimientos No Funcionales 🏗️

### 🔒 Seguridad
- Cifrado de contraseñas con **bcrypt** 🔐.
- Cumplimiento de normativas **GDPR** para protección de datos 📜.
- **Backups automáticos** para evitar pérdida de información 🛡️.

### 🚀 Escalabilidad y Rendimiento
- Uso de **Docker** para contenedorización 🐳.
- Implementación de **Redis** para caché y optimización 🚀.
- **Balanceo de carga** para alta disponibilidad 📡.

### 🔍 Usabilidad y Experiencia de Usuario
- Interfaz intuitiva y fácil de navegar 🖥️.
- Optimización para dispositivos móviles 📱.
- Soporte para múltiples idiomas 🌍.

## 3️⃣ Infraestructura y Tecnologías 🏛️

### Backend
- **NestJS** como framework principal ⚙️.
- **PostgreSQL** como base de datos 🗄️.
- **TypeORM** para la gestión de entidades y relaciones 🔄.

### Despliegue
- Uso de **CI/CD** para despliegues automatizados 🚀.
- Monitoreo y logs con herramientas como **Prometheus y Grafana** 📊.

---

## 📅 Plan de Desarrollo y Responsabilidades 📋

| Actividad | Responsable | Fecha de Inicio | Fecha de Fin | Estado |
|-----------|------------|----------------|-------------|--------|
| 📌 Definición de requerimientos | Product Owner | - | - | ✅ Completado |
| 🏗️ Diseño de arquitectura del sistema | Arquitecto de Software | - | - | ⏳ En proceso |
| 🔧 Desarrollo del Backend (NestJS) | Equipo Backend | - | - | 🔜 Pendiente |
| 🔐 Desarrollo del sistema de autenticación | Equipo Backend | - | - | 🔜 Pendiente |
| 🗄️ Implementación de base de datos (PostgreSQL) | DBA | - | - | 🔜 Pendiente |
| 🔄 Integración de TypeORM y relaciones de datos | Equipo Backend | - | - | 🔜 Pendiente |
| 👥 Implementación de gestión de usuarios | Equipo Backend | - | - | 🔜 Pendiente |
| 📚 Implementación de gestión de cursos | Equipo Backend | - | - | 🔜 Pendiente |
| 💳 Implementación de pasarela de pagos | Equipo Backend | - | - | 🔜 Pendiente |
| 🎨 Desarrollo del Frontend | Equipo Frontend | - | - | 🔜 Pendiente |
| 🧪 Pruebas de integración y seguridad | QA Team | - | - | 🔜 Pendiente |
| 🚀 Despliegue en entorno de producción | DevOps | - | - | 🔜 Pendiente |
| 📊 Monitoreo post-despliegue y optimización | DevOps | - | - | 🔜 Pendiente |

### Autores
* 👥 Luis Reyes
* 👥 Leonel Cordova