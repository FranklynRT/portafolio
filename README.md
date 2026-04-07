# Sistema de Gestión de Contratación CAS - UGEL Talara

![Estado](https://img.shields.io/badge/Estado-Finalizado-blue)
![Tecnologías](https://img.shields.io/badge/Stack-React%20%7C%20Node.js%20%7C%20MySQL-brightgreen)

Proyecto de innovación desarrollado para la optimización y digitalización del proceso de contratación bajo el régimen **CAS (Contratación Administrativa de Servicios)** en la UGEL Talara.

## 📝 Descripción
El sistema automatiza el flujo de reclutamiento y selección, permitiendo a los postulantes gestionar sus expedientes de manera digital y facilitando a Recursos Humanos la revisión, calificación y seguimiento de los procesos.

## 🚀 Características Principales

- **Gestión de Postulantes:** Registro, inicio de sesión y gestión de perfil personal.
- **Carga de Documentación:** Subida segura de CV y anexos obligatorios (formato PDF).
- **Seguimiento de Expedientes:** Visualización del estado del proceso (Enviado, En Revisión, Registrado, Rechazado).
- **Panel Administrativo:** Control total de convocatorias y calificación de postulantes por parte de RR.HH.
- **Validación de Datos:** Restricciones de formato para asegurar la integridad de la información.

## 🛠️ Stack Tecnológico

- **Frontend:** React.js
- **Backend:** Node.js
- **Base de Datos:** MySQL
- **Arquitectura:** Modelo-Vista-Controlador (MVC)

## 📋 Especificaciones Técnicas (Anexos)

- **Formatos de Archivo:** PDF únicamente para documentos; JPG/PNG para fotos.
- **Tamaño Máximo:** 10 MB por archivo.
- **Campos Obligatorios:** Validación estricta de datos personales, académicos y laborales.

## 🏗️ Estructura del Proyecto

```text
/
├── client/        # Interfaz de usuario (React)
├── server/        # API y lógica de negocio (Node.js)
├── database/      # Scripts y migraciones (MySQL)
└── docs/          # Documentación técnica adicional
