# 🐾 Sistema de Gestión de Refugio de Animales

Este proyecto es una aplicación de escritorio desarrollada en **Python** con la librería **Tkinter**, diseñada para facilitar la gestión de animales en un refugio. Permite el registro, seguimiento y control de los animales, así como el manejo de procesos de adopción y recuperación, todo desde una interfaz gráfica amigable.

---

## 📋 Descripción General

El sistema proporciona una plataforma centralizada para que el personal del refugio pueda:

- Registrar animales con todos sus datos.
- Ver listados de animales según su estado (en adopción, adoptados, en recuperación).
- Registrar procesos de adopción.
- Buscar animales por distintos filtros.
- Generar reportes en formato Excel.
- Administrar usuarios (solo administradores).


Todo esto se realiza desde una interfaz intuitiva con menús y botones, ideal para usuarios sin conocimientos técnicos.

---

## 🚀 Funcionalidades

- ✅ **Registro de animales** con información completa (nombre, especie, raza, edad, estado de salud, foto, etc.).
- ✅ **Listado de animales para adoptar**, adoptados o en recuperación.
- ✅ **Formulario de adopción** para registrar nuevos procesos con datos del adoptante.
- ✅ **Listado de animales ya adoptados** con la informacion completa del adoptante.
- ✅ **Listado de animales en recuperacion** muestra los animales segun el estado de salud en el que se encuentran
- ✅ **Búsqueda avanzada** de animales por filtros: nombre, especie, raza, edad, salud, estado de adopción.
- ✅ **Edición y eliminación lógica** de animales (pueden recuperarse luego).
- ✅ **Reportes Excel** con filtros por estado (adoptados, en adopción, en recuperación o todos), dependiendo la necesidad.
- ✅ **Gestión de usuarios**, solo visible para administradores, no para empleados.
- ✅ **Diseño adaptable** con panel lateral y área de contenido principal.

---

## 🛠 Tecnologías Utilizadas

- **Python 3**
- **Tkinter** – para la interfaz gráfica.
- **SQLite3** – como base de datos local.
- **Pandas** – para la generación de reportes en Excel.
- **Pillow (PIL)** – para carga y manejo de imágenes.

---

## 📦 Estructura del Proyecto

📁 refugio_animales/

│

├──  📁 assets/                  # Archivos estáticos (imágenes,íconos, etc.)

│   ㅤㅤ├── fondomain1.jpg

│   ㅤㅤ├── huella.ico

│

├── 📁 datos/                   # Archivos de datos y lógica de acceso a datos

│   ㅤㅤ├── adopciones.json

│   ㅤㅤ├── animales.json

│   ㅤㅤ├── datosusuarios.json

│   ㅤㅤ├── datos_adopciones.py

│   ㅤㅤ├── datos_animales.py

│   ㅤㅤ└── datos_usuarios.py

│

│

├── 📁 __pycache__/       ㅤㅤ  # Generado automáticamente por el sistema

│

├── buscar_animal.py      ㅤㅤ   # Módulo de búsqueda con filtros

├── editar_animales.py      ㅤㅤ  # Editar y eliminar animales

├── interfaz_inicio.py     ㅤㅤ  # Interfaz principal con el menú

├── lista_adopcion.py      ㅤㅤ  # Lista de animales en adopción

├── lista_adoptados.py     ㅤ    # Lista de animales adoptados

├── lista_recuperacion.py   ㅤ   # Animales en  recuperación

├── login.py            ㅤㅤ     # Módulo de inicio de sesión

├── #main.py ㅤㅤㅤㅤㅤㅤㅤ       # Punto de entrada principal de la aplicación

├── registrar_adopcion.py  ㅤ    # Registro de adopciones

├── registro_animal.py    ㅤㅤ    # Registro de nuevos animales

├── reportes.py         ㅤㅤㅤㅤ  # Generación de reportes Excel

└── README.md       ㅤㅤㅤㅤㅤ    # Documentación del proyecto


---

## 💻 Instalación y Ejecución

###  Clona o descarga este repositorio y ejecuta el arcivo main





---

## 👤 Autores
[Abraham Fuentes López] – Desarrollo de interfaz y funcionalidad general.

Gracias por revisar este proyecto. ¡Esperamos que ayude a mejorar la gestión de los refugios y la vida de muchos animales! 🐶🐱
