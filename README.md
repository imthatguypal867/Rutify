# Rutify
Plataforma fitness para crear, gestionar y solicitar programas y rutinas de entrenamiento.📊Profesionaliza tu gimnasio y comunicacion con tus alumnos. 🏋️‍♂️Optimiza tus entrenamientos y progreso.
Sistema de Gestión de Gimnasios y Entrenamiento Personal
Un sistema completo de gestión de gimnasios, entrenadores personales y estudiantes con funcionalidades avanzadas de seguimiento de entrenamientos, importación de rutinas y gestión de suscripciones.

## Tabla de Contenidos
- [Características Principales](#-características-principales)
- [Tipos de Usuario](#-tipos-de-usuario)
- [Funcionalidades por Usuario](#-funcionalidades-por-usuario)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Integraciones](#-integraciones)

##Características Principales
- **Autenticación Multi-rol** con NextAuth.js
- **Sistema de Registro y Verificación** por email
- **Redirección Inteligente** basada en roles de usuario
- **Sistema de Suscripciones y planes al sistema** para gimnasios y entrenadores
- **Dashboard Avanzado** con estadísticas en tiempo real
- **Diseño Responsive** optimizado para móviles
- **Importación de Rutinas** desde archivos Excel
- **Seguimiento de Progreso** con gráficos interactivos
- **Sistema de Notificaciones** push
- **Gestión de Objetivos** y programas personalizados
- **Calendario de Entrenamientos** integrado
- **Tracking de Sesiones** en tiempo real
- **Base de Datos Extensa de Ejercicios** con más de 400 ejercicios
- **Imágenes y Videos** de demostración para cada ejercicio
- **Historial Detallado** de progreso por ejercicio específico
- **Landing Page** con diseño moderno y responsive
- **Sistema de Recuperación de Contraseñas** con tokens seguros
- **PWA (Progressive Web App)** con instalación nativa
- **Imágenes Responsive** específicas para mobile/desktop

## 👥 Tipos de Usuario

### 1. **ADMIN** - Administrador del Sistema
### 2. **GYM_ADMIN** - Administrador de Gimnasio
### 3. **TEACHER** - Profesor/Entrenador
### 4. **USER** - Alumno/Cliente

## 🎯 Funcionalidades por Usuario

### 🔧 **ADMIN - Administrador del Sistema**

#### Gestión de Gimnasios
- **Crear/Editar Gimnasios** con información completa
- **Asignar Administradores** a gimnasios
- **Gestión de Planes** de suscripción (BASIC, STANDARD, PREMIUM)
- **Límites de Profesores** según el plan (1-3, 4-7, 8+)
- **Estadísticas Globales** de todos los gimnasios

#### Gestión de Personal Trainers
-  **Crear/Editar Personal Trainers** independientes
-  **Asignar Planes** de suscripción (BASIC, STANDARD, PREMIUM)
-  **Límites de Estudiantes** según el plan (1-5, 6-10, 11+)
-  **Gestión de Estados** (activo/inactivo)

#### Sistema de Limpieza
-  **Cleanup Automático** de datos obsoletos
-  **Gestión de Archivos** temporales
-  **Optimización de Base de Datos**

#### Gestión de Usuarios
-  **Verificación de Emails** pendientes
-  **Gestión de Tokens** de verificación
-  **Sistema de Feedback** de usuarios
-  **Monitoreo de Registros** y actividad

### 🏢 **GYM_ADMIN - Administrador de Gimnasio**

#### Gestión de Profesores
-  **Agregar/Remover Profesores** del gimnasio
-  **Ver Límites** actuales vs máximos (ej: "2/3 profesores")
-  **Restricciones por Plan** de suscripción
-  **Gestión de Estados** de profesores

#### Estadísticas del Gimnasio
-  **Dashboard de Estadísticas** con gráficos
-  **Rankings de uso** del gimnasio
-  **Métricas de Rendimiento** del gimnasio
-  **Reportes de Uso** de la plataforma

#### Gestión de Alumnos
-  **Ver Alumnos** asignados al gimnasio
-  **Estadísticas de Participación**
-  **Gestión de Accesos**

### 👨‍🏫 **TEACHER - Profesor/Entrenador**

#### Gestión de Alumnos
-  **Agregar Alumnos** con búsqueda por nombre
-  **Ver Límites** actuales vs máximos (ej: "3/5 alumnos")
-  **Separación de Listas** (alumnos PT vs alumnos gimnasio)
-  **Restricciones por Plan** de suscripción

#### Creación de Programas
-  **Crear Programas** personalizados
-  **Importar Rutinas** desde Excel con ejercicios reales
-  **Template Descargable** con ejercicios de la base de datos
-  **Búsqueda de Ejercicios Similares** automática
-  **Asignar a Alumnos** programas completos
-  **Biblioteca Visual de Ejercicios** con imágenes
-  **Búsqueda Avanzada** por músculo, equipamiento y nombre

#### Gestión de Rutinas
-  **Crear Rutinas** con ejercicios específicos
-  **Configurar Series/Repeticiones** por ejercicio
-  **Ordenar Ejercicios** en la rutina
-  **Notas** por ejercicio

#### Seguimiento de Alumnos
-  **Ver Progreso** de cada Alumno
-  **Estadísticas Detalladas** por alumno
-  **Historial de Entrenamientos**
-  **Gráficos de Progreso** semanales/mensuales
-  **Historial por Ejercicio** de cada alumno
-  **Análisis de Progreso** por músculo y ejercicio específico

#### Dashboard de Actividad
-  **Actividades Recientes** de alumnos
-  **Estadísticas Personales** de enseñanza
-  **Calendario de Sesiones**
-  **Biblioteca de Ejercicios** con imágenes
-  **Análisis de Rendimiento** de alumnos por ejercicio

### 👤 **USER - Alumno/Cliente**

#### Registro y Autenticación
-  **Registro Completo** con validación de datos
-  **Verificación de Email** obligatoria
-  **Recuperación de Contraseñas** con tokens seguros
-  **Login con Google** OAuth integrado
-  **Redirección Automática** según rol de usuario
-  **Sistema de Feedback** para reportar problemas

#### Gestión de Programas Propios Libre
-  **Crear Programas** personales
-  **Importar Rutinas** desde Excel
-  **Editar Programas** existentes

#### Programas Asignados en caso de que su gimnasio/PT este suscripto al sistema
-  **Ver Programas** asignados por profesores/PTs
-  **Diferenciar Origen** (profesor vs Personal Trainer)
-  **Estados de Programas** (activo/inactivo)
-  **Filtros por Objetivo** (ganar músculo, fuerza, etc.)

#### Entrenamientos
-  **Iniciar Sesiones** de entrenamiento
-  **Tracking en Tiempo Real** de ejercicios
-  **Registrar Series/Repeticiones/Peso**
-  **Continuar Sesiones** interrumpidas
-  **Historial Completo** de entrenamientos
-  **Visualización de Ejercicios** con imágenes y videos
-  **Instrucciones Detalladas** de ejecución correcta
-  **Biblioteca de Ejercicios** con más de 400 opciones

#### Seguimiento de Progreso
-  **Dashboard de Progreso** personal
-  **Gráficos de Volumen** semanal
-  **Estadísticas por Grupo Muscular**
-  **Tendencias de Rendimiento**
-  **Historial Completo de Ejercicios** con gráficos detallados
-  **Progreso por Ejercicio Específico** con evolución de peso y repeticiones
-  **Análisis de Rendimiento** por músculo y ejercicio

#### Perfil y Configuración
-  **Editar Perfil** personal
-  **Registrar Peso Corporal** con gráficos
-  **Configurar Notificaciones**
-  **Gestión de Preferencias**
-  **Subida de Fotos de Perfil** con Cloudinary

## 🛠️ Tecnologías Utilizadas

### **Frontend**
- **Next.js 14** - Framework React con App Router
- **TypeScript** - Tipado estático para mayor seguridad
- **Tailwind CSS** - Framework CSS utility-first
- **Heroicons** - Iconografía consistente
- **React Hook Form** - Gestión de formularios
- **Recharts** - Gráficos interactivos
- **XLSX** - Procesamiento de archivos Excel
- **Biblioteca Visual** - Componentes para mostrar ejercicios con imágenes

### **Backend**
- **Next.js API Routes** - API REST integrada
- **Prisma ORM** - ORM moderno para TypeScript
- **PostgreSQL** - Base de datos relacional
- **NextAuth.js** - Autenticación y autorización
- **Zod** - Validación de esquemas

### **Base de Datos**
- **PostgreSQL** - Base de datos principal
- **Prisma Migrations** - Control de versiones de BD
- **Soft Deletes** - Eliminación lógica de datos
- **Relaciones Complejas** - Múltiples tipos de relaciones
- **Base de Datos de Ejercicios** - Más de 500 ejercicios con imágenes
- **Multimedia de Ejercicios** - Videos e imágenes de demostración

### **Autenticación y Seguridad**
- **NextAuth.js** - Sistema de autenticación completo
- **JWT Tokens** - Tokens de sesión seguros
- **Role-based Access Control** - Control de acceso por roles
- **Email Verification** - Verificación obligatoria por email
- **Password Reset** - Recuperación segura de contraseñas
- **Google OAuth** - Login social integrado
- **Middleware Protection** - Protección de rutas por roles

### **Despliegue y Hosting**
- **Vercel** - Plataforma de despliegue
- **Neon Database** - Base de datos PostgreSQL en la nube
- **Cloudinary** - Almacenamiento de imágenes y videos
- **Environment Variables** - Configuración segura

## 🔌 Integraciones

### **Base de Datos**
- **Neon PostgreSQL** - Base de datos principal
- **Prisma Studio** - Interfaz visual para la BD

### **Almacenamiento**
- **Cloudinary** - Imágenes y videos de ejercicios
- **CDN Global** - Distribución de contenido
- **Base de Datos de Ejercicios** - Más de 500 ejercicios con imágenes
- **Multimedia de Ejercicios** - Videos e imágenes de demostración
- **Fotos de Perfil** - Subida y gestión de imágenes de usuario
- **Imágenes Responsive** - Específicas para mobile/desktop

### **Notificaciones**
- **Web Push API** - Notificaciones push del navegador
- **Service Workers** - Notificaciones en segundo plano

### **Archivos**
- **XLSX.js** - Procesamiento de archivos Excel
- **FileReader API** - Lectura de archivos del cliente
- **Multimedia de Ejercicios** - Gestión de imágenes y videos
- **CDN de Ejercicios** - Distribución global de contenido multimedia
- **Email Templates** - Plantillas HTML para emails de verificación
- **Image Upload** - Subida de imágenes de perfil


Licencia
Este proyecto está bajo la Licencia MIT. Ver LICENSE para más detalles.

Soporte
Email: rutifyapp@gmail.com
Instagram: https://www.instagram.com/rutify.app/
X:https://x.com/rutifyapp
