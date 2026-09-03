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

### 📊 Panel de Control (Dashboard Principal)
Vista general del sistema donde el administrador puede visualizar métricas clave, productos con bajo stock y movimientos del mes.

<img width="1310" height="597" alt="Captura de pantalla 2026-09-02 171823" src="https://github.com/user-attachments/assets/02176e7d-900c-43d3-a5fc-20b9c4936d4f" />


---

<img width="1060" height="533" alt="Captura de pantalla 2026-09-02 171915" src="https://github.com/user-attachments/assets/01eadd36-5b5b-4f31-b06f-215734a04e4d" />

### 🤖 Asistente de Inteligencia Artificial y 📝 Carga Automatizada o Manual de Productos
Chatbot integrado capaz de leer la base de datos en tiempo real para auditar el stock y alertar sobre quiebres de inventario.

<img width="1138" height="549" alt="Captura de pantalla 2026-09-01 204817" src="https://github.com/user-attachments/assets/b55f2768-46d1-4149-b663-6de5826aa2ac" />

---

<img width="1333" height="591" alt="Captura de pantalla 2026-09-03 151002" src="https://github.com/user-attachments/assets/39497de5-3306-4b3a-9353-009e8d7e8505" />

---

<img width="1337" height="593" alt="Captura de pantalla 2026-09-03 151122" src="https://github.com/user-attachments/assets/391af8ee-49a9-45b5-a71a-70140997eb50" />


---
<img width="1127" height="545" alt="Captura de pantalla 2026-09-01 204724" src="https://github.com/user-attachments/assets/57b497ee-f8fd-424f-98cb-a68ae2410db0" />

---


### 📦 Gestión de Inventario (ABM)
Módulo administrativo completo que permite agregar, editar o eliminar productos del catálogo de forma ágil, aplicando validaciones estrictas para mantener la integridad de la base de datos.

<img width="1129" height="546" alt="Captura de pantalla 2026-09-01 210119" src="https://github.com/user-attachments/assets/31a27d18-bf47-4f0d-936e-efd179ad5b48" />

---
### ⏱️ Historial y Descuento de Stock Automático
Registro de movimientos en tiempo real. Al registrar el uso de un producto, el sistema descuenta automáticamente las unidades del inventario global y actualiza el historial sin necesidad de recargar la página.

<img width="1124" height="544" alt="Captura de pantalla 2026-09-01 210201" src="https://github.com/user-attachments/assets/5d3fcc39-91b3-4460-9816-20256057d1e8" />



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
