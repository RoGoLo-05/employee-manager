# Employee Manager 🏢

Sistema de gestión de empleados. Full Stack (Spring Boot/Java + Angular/TypeScript) con CRUD completo, gestión de departamentos y base de datos PostgreSQL.

## 🛠 Tech Stack

**Backend**
- Java 17 + Spring Boot 4
- Spring Data JPA + Hibernate
- PostgreSQL (Supabase)

**Frontend** *(en desarrollo)*
- Angular
- TypeScript
- TailwindCSS

## 🚀 Endpoints API

| Método | Ruta | Descripción |
|--------|------|-------------|
| GET | `/api/employees` | Obtener todos los empleados |
| GET | `/api/employees/{id}` | Obtener empleado por ID |
| POST | `/api/employees` | Crear empleado |
| PUT | `/api/employees/{id}` | Actualizar empleado |
| DELETE | `/api/employees/{id}` | Eliminar empleado |

## ⚙️ Variables de entorno

Crea un archivo `application.properties` con:
DB_PASSWORD=tu_contraseña_de_supabase

## 👤 Autor
Roberto Gómez López — [GitHub](https://github.com/RoGoLo-05)

