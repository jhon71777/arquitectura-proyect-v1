# arquitectura-proyect-v1

# EV_CHARGE 

## 🛠️ Tecnologías Utilizadas

*   **Python 3.13+**
*   **FastAPI** (Framework web de alto rendimiento)
*   **SQLAlchemy** (ORM para la gestión de la base de datos)
*   **PostgreSQL** (Sistema de gestión de bases de datos relacionales)
*   **Uvicorn** (Servidor ASGI para ejecutar la aplicación)
*   **pgAdmin** (Herramienta de administración para PostgreSQL)

# Estructura del Proyecto

```text
EV_CHARGE/
├── config/             # Configuración de la base de datos y conexiones
│   └── database.py
├── controllers/        # Lógica de negocio y controladores de las entidades
│   ├── empresa_controller.py
│   ├── punto_carga_controller.py
│   ├── user_controller.py
│   └── vehiculo_controller.py
├── routes/             # Enrutadores de las APIs (End-points)
│   ├── empresa_routes.py
│   ├── puntos_carga_routes.py
│   ├── user_routes.py
│   └── vehiculos_routes.py
├── schemas/            # Esquemas de validación de datos con Pydantic
│   ├── empresa_schema.py
│   ├── punto_carga_schema.py
│   ├── user_schema.py
│   └── vehiculo_schema.py
├── models.py           # Modelos de tablas de SQLAlchemy
├── main.py             # Punto de entrada de la aplicación FastAPI
└── requirements.txt    # Dependencias del proyecto

# Clonar el Repositorio
gh repo clone jhon71777/arquitectura-proyect-v1

Ingresar al proyecto:


Crear Entorno Virtual

python -m venv venv

Activar Entorno Virtual
Linux/Ubuntu/Lubuntu/Debian

source venv/bin/activate

Windows

venv\Scripts\activate

Instalar Dependencias
pip install -r requirements.txt

Ejecutar la Aplicación
uvicorn app.main:app --reload


Acceder a la API

Interfaz de usuario Swagger
http://127.0.0.1:8000/docs




Autores
