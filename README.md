# ✅ Tasks List

<div align="center">
  <img src="https://img.shields.io/badge/Django-6.0.7-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
</div>

<p align="center">
  <strong>Una aplicación sencilla y elegante para gestionar tareas con Django.</strong>
</p>

---

## 🚀 Descripción general

Tasks List es un proyecto base desarrollado con Django que permite organizar tareas mediante una interfaz minimalista y una arquitectura limpia. Está pensado como una solución práctica para aprender, extender o usar como punto de partida en aplicaciones de productividad.

---

## ✨ Características

- Gestión de tareas con modelo propio
- Registro automático de fechas de creación y actualización
- Diseño simple y adaptable para crecer
- Estructura modular compatible con Django
- Preparado para extender con funcionalidades adicionales como estado, prioridad o categorías

---

## 🛠️ Tecnologías utilizadas

- Python
- Django
- SQLite
- HTML + Templates
- Bootstrap-ready structure (lista para personalizar)

---

## 📁 Estructura del proyecto

```text
tasks_list/
├── django_base/         # Configuración principal del proyecto Django
├── tasks/               # Aplicación de tareas
├── templates/           # Plantillas HTML
├── db.sqlite3           # Base de datos local
├── manage.py            # Comando principal de Django
└── requirements.txt     # Dependencias del proyecto
```

---

## ⚙️ Instalación

1. Clona el repositorio:

```bash
git clone <url-del-repositorio>
cd tasks_list
```

2. Crea un entorno virtual:

```bash
python -m venv venv
```

3. Activa el entorno virtual:

```bash
venv\Scripts\activate
```

4. Instala las dependencias:

```bash
pip install -r requirements.txt
```

5. Realiza las migraciones:

```bash
python manage.py migrate
```

6. Ejecuta el servidor:

```bash
python manage.py runserver
```

Abre tu navegador en:

```text
http://127.0.0.1:8000/
```

---

## 🧪 Uso

La aplicación muestra la lista de tareas desde una vista basada en clases de Django. Puedes modificar el modelo y las vistas para agregar:

- tareas completadas
- categorías
- prioridades
- edición y eliminación
- autenticación de usuarios

---

## 🔧 Comandos útiles

```bash
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

---

## 🌟 Próximos pasos recomendados

- Añadir un formulario para crear nuevas tareas
- Implementar estado: pendiente / completada
- Agregar diseño con Tailwind o Bootstrap
- Integrar CRUD completo
- Crear una API REST con Django REST Framework

---

## 📌 Nota

Este proyecto funciona como una base limpia y escalable para desarrollar una aplicación de listas de tareas con Django, ideal para practicar o ampliar con nuevas funcionalidades.

---

<p align="center">
  <strong>Hecho con ❤️ y Django</strong>
</p>
