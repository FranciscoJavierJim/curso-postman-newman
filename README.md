# 🧪 Curso Postman + Newman

Este repositorio contiene prácticas realizadas con **Postman** para pruebas de APIs, junto con colecciones exportadas que pueden ejecutarse desde **Newman**, el runner de colecciones de Postman desde la línea de comandos. :contentReference[oaicite:1]{index=1}

---

## 🚀 ¿Qué contiene este proyecto?

El repositorio incluye:

📁 curso-postman-newman/
├── NEWMAN.postman_collection.json # Colección principal de pruebas
├── POSTMAN-ECHO.postman_collection.json # Colección de ejemplo con Postman Echo
├── POSTMAN-ECHO.postman_environment.json # Variables de entorno para la colección
└── .gitignore

Estas colecciones fueron exportadas desde Postman y están listas para ejecutar con **Newman**. :contentReference[oaicite:2]{index=2}

---

## 🧰 Tecnologías / Herramientas

- 🛠 **Postman** – herramienta para pruebas de APIs  
- 📦 **Newman** – ejecutor de colecciones de Postman desde la terminal :contentReference[oaicite:3]{index=3}
- 📝 Archivos JSON exportados para uso con Postman / Newman

---

## 📦 Instalación y uso

### 1️⃣ Instalar Newman (global o local)

Si no tienes Newman instalado globalmente:

```bash
npm install -g newman

O instálalo localmente en el proyecto:

npm install newman

▶️ Ejecutar las colecciones

🔹 Ejecutar la colección principal

newman run NEWMAN.postman_collection.json

🔹 Ejecutar la colección con entorno

newman run POSTMAN-ECHO.postman_collection.json -e POSTMAN-ECHO.postman_environment.json

🧠 ¿Qué se practica aquí?

Este proyecto sirve para practicar:

✔️ Cómo crear y organizar colecciones de pruebas en Postman
✔️ Cómo exportar y ejecutar esas pruebas desde la terminal
✔️ Cómo usar Newman para tener pruebas automatizadas CLI

👤 Autor

Francisco Javier Jiménez
GitHub: https://github.com/FranciscoJavierJim
