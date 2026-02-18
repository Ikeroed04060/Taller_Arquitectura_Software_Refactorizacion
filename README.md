# Taller_Arquitectura_Software_Refactorizacion
Repositorio para el taller práctico de refactorización de un sistema monolítico en microservicios. Se analizan y corrigen anti-patrones en el código, se aplican principios de Clean Code, y se propone una nueva arquitectura utilizando patrones de diseño y microservicios para mejorar escalabilidad y mantenibilidad.

## Integrantes del Grupo
1. **Nombre Integrante 1:** Iker Edwin Santiago Solano Ruiz
2. **Nombre Integrante 2:** Cesar David Quintero Ramirez
3. **Nombre Integrante 3:** Andy Brahiam Yara Medina

## Cómo Ejecutar el Proyecto

### Requisitos Previos
- Docker Desktop 4.0+
- Git 2.30+
- VS Code o cualquier IDE de tu preferencia

### Instrucciones de Instalación

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Ikeroed04060/Taller_Arquitectura_Software_Refactorizacion.git


### Tecnologías Utilizadas
- **Backend:** Spring Boot con Java (API REST)
- **Frontend:** Angular 17+ (SPA)
- **Base de datos:** PostgreSQL 15
- **Infraestructura:** Docker Compose

### Objetivos del Taller
1. **Identificación de Anti-Patrones:** Analizar y documentar anti-patrones en el código existente.
2. **Refactorización a Microservicios:** Proponer una arquitectura basada en microservicios, mejorando la escalabilidad y mantenibilidad.
3. **Aplicación de Clean Code:** Refactorizar el código siguiendo los principios de Clean Code.
4. **Propuesta de Patrones de Diseño:** Implementar patrones como MVC, Repository, DTO y otros para mejorar la estructura y organización del código.

## Fases del Proyecto

### Fase 1: Montaje, Exploración y Pruebas Funcionales
- **Montaje del entorno:** Clonación del repositorio, configuración de contenedores Docker y verificación de que todo funcione correctamente.
- **Pruebas funcionales:** Ejecución de pruebas de funcionalidad básicas, como la creación de encuestas, votaciones, y pruebas de seguridad como SQL Injection.

### Fase 2: Análisis de Anti-Patrones y Malas Prácticas
- **Backend:** Identificación de problemas como SQL Injection, credenciales hardcodeadas, y violaciones del principio SOLID (SRP).
- **Frontend:** Análisis de problemas en el código Angular, como el uso de URL hardcodeadas, falta de tipado y uso incorrecto de HttpClient.

### Fase 3: Propuesta de Valor y Rediseño Arquitectónico
- **Patrones de Diseño:** Propuesta de soluciones para los anti-patrones identificados, usando arquitecturas en capas y patrones como Repository y DTO.
- **Clean Code:** Aplicación de principios como DRY (Don't Repeat Yourself), manejo adecuado de errores y nombrado significativo.
- **Microservicios:** Descomposición del monolito en microservicios con responsabilidades claras, como `survey-service` y `voting-service`.

### Fase 4: Entregables
- **Informe de Montaje:** Con resultados de las pruebas funcionales realizadas.
- **Análisis de Anti-Patrones:** Documento con los anti-patrones identificados y justificación de las soluciones propuestas.
- **Diagramas de C4:** Diagramas que ilustran la arquitectura actual y la propuesta de microservicios.
- **Propuesta Final:** Documento con los detalles de la nueva arquitectura, patrones de diseño aplicados, y los ADR (Architecture Decision Records).

## Estructura del Proyecto
<img width="520" height="490" alt="image" src="https://github.com/user-attachments/assets/4ccae585-c998-4665-8953-b977de5c7ee7" />




