# Backend — API Organizador de Actividades (TaskFlow)

API RESTful desarrollada con **Django** y **Django REST Framework** (DRF), correspondiente a la arquitectura base del sistema de gestión de tareas y eventos (Sección 6 del Backlog Refinado).

- **Front-end:** React (SPA) — Repositorio independiente.
- **Back-end:** Servicio REST API en Django.
- **Persistencia:** PostgreSQL gestionado en **Supabase** (en entorno de producción vía `DATABASE_URL`) y SQLite para ejecución local.

---

## 🛠️ Desarrollo e Instalación Local

### Requisitos Previos
* Python 3.10+
* Virtualenv

### Pasos de Configuración

1. **Creación y activación del entorno virtual:**
   ```bash
   python -m venv venv
   # En Windows:
   venv\Scripts\activate
   # En Linux/macOS:
   source venv/bin/activate