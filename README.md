# Rutify
Plataforma fitness para crear, gestionar y solicitar programas y rutinas de entrenamiento.📊Profesionaliza tu gimnasio y comunicacion con tus alumnos. 🏋️‍♂️Optimiza tus entrenamientos y progreso.
Sistema de Gestión de Gimnasios y Entrenamiento Personal
Un sistema completo de gestión de gimnasios, entrenadores personales y estudiantes con funcionalidades avanzadas de seguimiento de entrenamientos, importación de rutinas y gestión de suscripciones.

Tabla de Contenidos
Características Principales

Tipos de Usuario

Funcionalidades por Usuario

Tecnologías Utilizadas

Integraciones

Características Principales
Autenticación Multi-rol con NextAuth.js

Sistema de Registro y Verificación por email

Redirección Inteligente basada en roles de usuario

Sistema de Suscripciones para gimnasios y entrenadores

Dashboard Avanzado con estadísticas en tiempo real

Diseño Responsive optimizado para móviles

Importación de Rutinas desde archivos Excel

Seguimiento de Progreso con gráficos interactivos

Sistema de Notificaciones push

Gestión de Objetivos y programas personalizados

Calendario de Entrenamientos integrado

Tracking de Sesiones en tiempo real

Base de Datos Extensa de Ejercicios con más de 500 ejercicios

Imágenes y Videos de demostración para cada ejercicio

Historial Detallado de progreso por ejercicio específico

Landing Page Mejorada con diseño moderno y responsive

Sistema de Recuperación de Contraseñas con tokens seguros

PWA (Progressive Web App) con instalación nativa

Imágenes Responsive específicas para mobile/desktop

Tipos de Usuario
ADMIN - Administrador del Sistema

GYM_ADMIN - Administrador de Gimnasio

TEACHER - Profesor/Entrenador

USER - Alumno/Cliente

Funcionalidades por Usuario
ADMIN - Administrador del Sistema
Gestión de Gimnasios

Crear/Editar Gimnasios con información completa

Asignar Administradores a gimnasios

Gestión de Planes de suscripción (BASIC, STANDARD, PREMIUM)

Límites de Profesores según el plan (1-3, 4-7, 8+)

Estadísticas Globales de todos los gimnasios

Gestión de Personal Trainers

Crear/Editar Personal Trainers independientes

Asignar Planes de suscripción (BASIC, STANDARD, PREMIUM)

Límites de Estudiantes según el plan (1-5, 6-10, 11+)

Gestión de Estados (activo/inactivo)

Sistema de Limpieza

Cleanup Automático de datos obsoletos

Gestión de Archivos temporales

Optimización de Base de Datos

Gestión de Usuarios

Verificación de Emails pendientes

Gestión de Tokens de verificación

Sistema de Feedback de usuarios

Monitoreo de Registros y actividad

GYM_ADMIN - Administrador de Gimnasio
Gestión de Profesores

Agregar/Remover Profesores del gimnasio

Ver Límites actuales vs máximos (ej: "2/3 profesores")

Restricciones por Plan de suscripción

Gestión de Estados de profesores

Estadísticas del Gimnasio

Dashboard de Estadísticas con gráficos

Rankings de Profesores por actividad

Métricas de Rendimiento del gimnasio

Reportes de Uso de la plataforma

Gestión de Alumnos

Ver Alumnos asignados al gimnasio

Estadísticas de Participación

Gestión de Accesos

TEACHER - Profesor/Entrenador
Gestión de Alumnos

Agregar Alumnos con búsqueda por nombre

Ver Límites actuales vs máximos (ej: "3/5 alumnos")

Separación de Listas (alumnos PT vs alumnos gimnasio)

Restricciones por Plan de suscripción

Creación de Programas

Crear Programas personalizados

Importar Rutinas desde Excel con ejercicios reales

Template Descargable con ejercicios de la base de datos

Búsqueda de Ejercicios Similares automática

Asignar a Alumnos programas completos

Biblioteca Visual de Ejercicios con imágenes y videos

Búsqueda Avanzada por músculo, equipamiento y nombre

Gestión de Rutinas

Crear Rutinas con ejercicios específicos

Configurar Series/Repeticiones por ejercicio

Ordenar Ejercicios en la rutina

Notas y Peso Sugerido por ejercicio

Seguimiento de Alumnos

Ver Progreso de cada Alumno

Estadísticas Detalladas por alumno

Historial de Entrenamientos

Gráficos de Progreso semanales/mensuales

Historial por Ejercicio de cada alumno

Análisis de Progreso por músculo y ejercicio específico

Dashboard de Actividad

Actividades Recientes de alumnos

Estadísticas Personales de enseñanza

Calendario de Sesiones

Biblioteca de Ejercicios con imágenes y videos

Análisis de Rendimiento de alumnos por ejercicio

USER - Alumno/Cliente
Registro y Autenticación

Registro Completo con validación de datos

Verificación de Email obligatoria

Recuperación de Contraseñas con tokens seguros

Login con Google OAuth integrado

Redirección Automática según rol de usuario

Sistema de Feedback para reportar problemas

Gestión de Programas Propios Libre

Crear Programas personales

Importar Rutinas desde Excel

Editar Programas existentes

Programas Asignados

Ver Programas asignados por profesores/PTs

Diferenciar Origen (profesor vs Personal Trainer)

Estados de Programas (activo/inactivo)

Filtros por Objetivo (ganar músculo, fuerza, etc.)

Entrenamientos

Iniciar Sesiones de entrenamiento

Tracking en Tiempo Real de ejercicios

Registrar Series/Repeticiones/Peso

Continuar Sesiones interrumpidas

Historial Completo de entrenamientos

Visualización de Ejercicios con imágenes y videos

Instrucciones Detalladas de ejecución correcta

Biblioteca de Ejercicios con más de 500 opciones

Seguimiento de Progreso

Dashboard de Progreso personal

Gráficos de Volumen semanal

Estadísticas por Grupo Muscular

Tendencias de Rendimiento

Historial Completo de Ejercicios con gráficos detallados

Progreso por Ejercicio Específico con evolución de peso y repeticiones

Perfil y Configuración

Editar Perfil personal

Registrar Peso Corporal con gráficos

Configurar Notificaciones

Gestión de Preferencias

Subida de Fotos de Perfil con Cloudinary

Tecnologías Utilizadas
Frontend

Next.js 14

TypeScript

Tailwind CSS

Heroicons

React Hook Form

Recharts

XLSX

Biblioteca Visual de ejercicios

Backend

Next.js API Routes

Prisma ORM

PostgreSQL

NextAuth.js

Zod

Base de Datos

PostgreSQL

Prisma Migrations

Soft Deletes

Relaciones Complejas

Base de Datos de Ejercicios (500+)

Multimedia de Ejercicios

Autenticación y Seguridad

NextAuth.js

JWT Tokens

Role-based Access Control

Session Management

Email Verification

Password Reset

Google OAuth

Middleware Protection

Despliegue y Hosting

Vercel

Neon Database

Cloudinary

Environment Variables

Integraciones
Base de Datos

Neon PostgreSQL

Prisma Studio

Almacenamiento

Cloudinary

CDN Global

Notificaciones

Web Push API

Service Workers

Archivos

XLSX.js

FileReader API

Email

Plantillas HTML para verificación

Subida de imágenes de perfil

Licencia
Este proyecto está bajo la Licencia MIT. Ver LICENSE para más detalles.

Soporte
Email: rutifyapp@gmail.com
Discord: [Servidor de la comunidad]
Documentación: [Enlace a docs]