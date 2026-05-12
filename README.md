<div align="center">

  # Wavii Organization

  **Tu música. Tu ritmo. Tu comunidad.**

  <p align="center">
    Wavii es una plataforma de aprendizaje musical gamificado (TFG 2DAM).<br/>
    Nuestro objetivo es hacer que el aprendizaje musical sea accesible, interactivo y comunitario.
  </p>

  <div>
    <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" />
    <img src="https://img.shields.io/badge/Expo-1B1F23?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
    <img src="https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot" alt="Spring Boot" />
    <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java 21" />
    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
    <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
    <img src="https://img.shields.io/badge/Odoo-714B67?style=for-the-badge&logo=odoo&logoColor=white" alt="Odoo" />
  </div>
</div>

<br/>

## Acerca de Wavii

Wavii engloba todos los servicios de la aplicación móvil de aprendizaje musical. El ecosistema está diseñado para ofrecer una experiencia fluida tanto a estudiantes principiantes como a músicos avanzados, integrando módulos de lecciones, sistema de profesores certificados y funciones sociales.
- [Sobre el proyecto](https://wavii-project.github.io/about-us/)
- [Código de la app](https://github.com/Wavii-Project/wavii-app)

### Principales características

- **Aprendizaje interactivo:** Lecciones estructuradas por niveles (Principiante, Intermedio, Avanzado).
- **Gamificación:** Sistema de experiencia (XP), rachas diarias y seguimiento de progreso para mantener la motivación.
- **Comunidad y Profesores:** Integración de Profesores Particulares y Profesores Certificados.
- **Suscripciones Premium:** Integración con pasarelas de pago para acceder a funciones Plus y planes de educación (Scholar).
- **Gestión Empresarial:** Panel administrativo con Odoo para verificación de profesores y contabilidad.

## Arquitectura y Tecnologías

Nuestro ecosistema técnico está dividido en los siguientes pilares fundamentales:

### Frontend
- **Framework:** Expo SDK 54 / React Native
- **Lenguaje:** TypeScript estricto
- **Navegación:** React Navigation v7
- **Gestión de Estado:** Zustand
- **Autenticación:** SecureStore para JWT y AsyncStorage

### Backend
- **Framework:** Spring Boot 3 / Java 21
- **Persistencia Relacional:** PostgreSQL 16 (Usuarios, tokens, suscripciones)
- **Persistencia Documental:** MongoDB 7 (Contenido musical, lecciones)
- **Seguridad:** JWT (JSON Web Tokens)
- **Integraciones:** Stripe (Pagos), Twilio (SMS), JavaMailSender (Emails)

### Infraestructura y Operaciones
- **Contenedores:** Docker y Docker Compose
- **Proxy Inverso:** Nginx
- **ERP:** Odoo 17 (Gestión de profesores, finanzas)

---

<div align="center">
  <p>Creado con pasion para el TFG de 2DAM.</p>
</div>
