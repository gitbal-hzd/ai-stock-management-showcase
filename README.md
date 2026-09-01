# ai-stock-management-showcase
# 📦 Sistema Inteligente de Gestión de Stock (AI-Powered)

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-181818?style=for-the-badge&logo=supabase&logoColor=3ECF8E)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

> ⚠️ **Nota Importante:** El código fuente de este proyecto se mantiene en un repositorio privado por motivos de propiedad intelectual y uso comercial del negocio. Este repositorio público sirve como **documentación, demostración de arquitectura y portafolio** de las tecnologías implementadas.

## 🚀 Descripción del Proyecto
Una plataforma web Full Stack diseñada para automatizar y optimizar el control de inventario físico en tiempo real. El sistema elimina la carga manual repetitiva e integra un asistente conversacional basado en Inteligencia Artificial para auditoría, control de faltantes y predicción de stock.

## ✨ Funcionalidades Principales
- **Control de Inventario en Tiempo Real:** Gestión de entradas, salidas y actualizaciones de stock sincronizadas de forma instantánea.
- **Asistente de IA (Chat Inteligente):** Bot conversacional que permite consultar productos agotados, niveles de inventario actuales y analizar la demanda.
- **Carga Automatizada:** Flujos optimizados para la inserción rápida de nuevos productos en la base de datos.
- **Validación Robusta:** Formularios estrictos para evitar errores humanos (data entry).

## 📸 Interfaz y Demostración
<img width="1330" height="580" alt="Captura de pantalla 2026-09-01 204445" src="https://github.com/user-attachments/assets/ba09bc18-5be4-4d63-b077-7a9cf9b6521f" />
<img width="1138" height="549" alt="Captura de pantalla 2026-09-01 204817" src="https://github.com/user-attachments/assets/b55f2768-46d1-4149-b663-6de5826aa2ac" />
<img width="1127" height="545" alt="Captura de pantalla 2026-09-01 204724" src="https://github.com/user-attachments/assets/57b497ee-f8fd-424f-98cb-a68ae2410db0" />


## 🛠️ Arquitectura y Stack Tecnológico

### Frontend
* **Core:** React.js + TypeScript (empaquetado con Vite)
* **Estilos:** Tailwind CSS para una interfaz moderna y responsive.
* **Manejo de Estado:** TanStack Query (React Query) para caché, sincronización asíncrona y mutaciones.
* **Formularios:** React Hook Form + Zod para validación estricta de esquemas en el cliente.

### Backend, Cloud & IA
* **Base de Datos & Auth:** Supabase (PostgreSQL).
* **Despliegue (Hosting):** Vercel (Frontend) y Render.
* **Inteligencia Artificial:** Integración de IA para procesamiento de consultas de inventario mediante lenguaje natural.

## 🧠 Soluciones Técnicas Implementadas
* **Sincronización de Estado:** Se implementó TanStack Query para garantizar que la interfaz siempre refleje la base de datos real (Supabase) sin necesidad de recargar la página, manejando estados de carga y error de manera súper fluida.
* **Validación de Tipos de Extremo a Extremo:** Gracias al uso conjunto de TypeScript, Zod y Supabase, se garantizó que los datos fluyan sin errores desde la base de datos hasta los componentes de React.

---
**Desarrollado por:** Baltazar Martinez
[LinkedIn](https://www.linkedin.com/in/baltazarmartinez) | [GitHub](https://github.com/gitbal-hzd)
