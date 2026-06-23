# 🚀 Proyecto: API REST con Express.js

**Curso:** Transformación Digital para la Docencia Técnica 3  
**Catedrática:** Profe Dina 👩‍🏫  

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white)
![API REST](https://img.shields.io/badge/API_REST-005571?style=for-the-badge)

---

## 📖 Descripción del Proyecto

Como parte de la capacitación en el **Curso Transformación Digital para la Docencia Técnica 3**, hemos desarrollado esta API RESTful utilizando **Node.js** y el framework **Express.js**. 

El objetivo principal de este proyecto es demostrar la creación de un servidor backend funcional capaz de manejar peticiones HTTP, rutas (endpoints) y procesar datos en formato JSON, aplicando los conceptos de transformación digital en entornos educativos.

---

## 🌐 Arquitectura de la API

A continuación, presentamos un esquema visual de la estructura de nuestra API y cómo gestiona las peticiones:

> 🖼️ **Nota para el equipo:** Suban su propio diagrama de flujo a la carpeta del repositorio y cambien este enlace. Ejemplo: `![Diagrama de Arquitectura](./docs/esquema-api.png)`

![Esquema de Express.js](https://upload.wikimedia.org/wikipedia/commons/6/64/Expressjs.png)
*(Reemplazar con el diagrama de la arquitectura del proyecto)*

### 📌 Endpoints Desarrollados

La API cuenta con las siguientes rutas configuradas para su evaluación:

| Método | Endpoint | Descripción |
| :--- | :--- | :--- |
| **GET** | `/api/recursos` | Obtiene la lista completa de recursos. |
| **GET** | `/api/recursos/:id` | Obtiene un recurso específico por su ID. |
| **POST** | `/api/recursos` | Agrega un nuevo recurso al sistema. |
| **PUT** | `/api/recursos/:id` | Actualiza los datos de un recurso existente. |
| **DELETE** | `/api/recursos/:id` | Elimina un recurso de la base de datos. |

### 📸 Evidencia de Funcionamiento

Captura de pantalla de las pruebas realizadas (Ej. Postman, Thunder Client o Insomnia):

> 🖼️ **Nota para el equipo:** Suban su captura de prueba a la carpeta del repositorio y cambien este enlace. Ejemplo: `![Prueba GET](./docs/prueba-postman.png)`

![Prueba de la API](https://via.placeholder.com/800x400.png?text=Sube+aqui+una+captura+de+pantalla+probando+los+endpoints+con+Express.js)

---

## ⚙️ Instrucciones de Instalación y Despliegue

Pasos para que la profe Dina pueda ejecutar el servidor en su entorno local:

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/](https://github.com/)[tu-usuario]/[nombre-del-repositorio].git
