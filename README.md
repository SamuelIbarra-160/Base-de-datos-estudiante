# 📚 Sistema de Gestión de Estudiantes

Aplicación de escritorio desarrollada en **Python** utilizando **Tkinter** para la interfaz gráfica y **SQLite** como base de datos.

Este proyecto permite administrar un registro de estudiantes mediante las operaciones básicas de un CRUD (Crear, Leer, Actualizar y Eliminar).

---

## 🚀 Características

- Agregar nuevos estudiantes.
- Editar información existente.
- Eliminar registros.
- Visualizar todos los estudiantes en una tabla.
- Almacenamiento permanente mediante SQLite.
- Interfaz gráfica sencilla e intuitiva.

---

## 🛠️ Tecnologías utilizadas

- Python 3
- Tkinter
- SQLite3

---

## 📂 Estructura del proyecto

```
📁 Sistema-Estudiantes
│
├── main.py
├── estudiantes.db
└── README.md
```

---

## ▶️ Cómo ejecutar el proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/tuusuario/sistema-estudiantes.git
```

2. Entrar a la carpeta del proyecto:

```bash
cd sistema-estudiantes
```

3. Ejecutar el programa:

```bash
python main.py
```

No es necesario instalar librerías adicionales, ya que **Tkinter** y **SQLite3** vienen incluidos con la instalación estándar de Python.

---

## 🖥️ Funcionalidades

- Registro de estudiantes.
- Consulta de registros almacenados.
- Modificación de información.
- Eliminación de registros.
- Actualización automática de la tabla.

---

## 📸 Vista del sistema

Puedes agregar aquí una captura de pantalla del programa.

Ejemplo:

```
📷 screenshots/sistema.png
```

y luego mostrarla con:

```markdown
![Sistema](screenshots/sistema.png)
```

---

## ⚠️ Nota

Actualmente el proyecto almacena únicamente:

- Nombre
- Carrera
- Nota

Aunque la interfaz incluye campos para:

- Apellidos
- Correo
- Teléfono

estos aún no se encuentran registrados en la base de datos. Se pueden agregar fácilmente modificando la estructura de la tabla SQLite y las funciones CRUD.

---

## 📈 Mejoras futuras

- Buscar estudiantes.
- Validación de correo electrónico.
- Validación de número telefónico.
- Exportar datos a Excel o PDF.
- Diseño moderno con CustomTkinter.
- Sistema de usuarios e inicio de sesión.

---

## 👨‍💻 Autor

Desarrollado por **Samuel Ibarra** como proyecto de práctica para el aprendizaje de Python, Tkinter y SQLite.
