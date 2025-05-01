# DragAndList

**Drag & List** es una aplicación de gestión de tareas estilo Trello, construida con React, Vite, Express y PostgreSQL. Permite crear tableros, listas y tareas con funcionalidad de **drag & drop** entre listas usando `dnd-kit`.

---

##  Demo en Producción

 **Frontend**: [https://dragandlist.netlify.app](https://dragandlist.netlify.app)  
 **Backend (API)**: [https://dragandlist-backend.onrender.com](https://dragandlist-backend.onrender.com)

---

## Tecnologías utilizadas

### Frontend:
-  React + Vite
-  Bootstrap 5
- dnd-kit (drag & drop)
- Fetch API + `.env`

### Backend:
-  Express.js (ESM modules)
-  PostgreSQL
-  Sequelize-like lógica propia (con JSON / PG)
-  CORS configurado para entornos producción y desarrollo

---

##  Funcionalidades principales

- Crear y eliminar **tableros**  
- Crear y eliminar **listas** dentro de tableros  
- Crear, eliminar y marcar como completadas las **tareas**  
- Mover tareas entre listas (drag & drop)  
- Reordenar listas con drag & drop  
- Persistencia de datos con PostgreSQL  
- Integración entre frontend y backend desplegado



##  Estructura del repositorio
dragandlist_frontend/ 
│ ├── src/ 
│ ├── components/ 
│ │ ├── BoardForm.jsx 
│ │ ├── Boards.jsx 
│ │ ├── BoardLists.jsx 
│ │ ├── TaskForm.jsx 
│ │ └── ListForm.jsx 
│ ├── App.jsx 
│ └── main.jsx 
│ ├── public/ 
├── .env 
└── README.md

 dragandlist_backend/
│
├── database/
│   └── connection.js        # Configura y conecta a PostgreSQL
│
├── models/
│   ├── board.model.js       # Lógica y queries para tableros
│   ├── list.model.js        # Lógica y queries para listas
│   └── task.model.js        # Lógica y queries para tareas
│
├── routes/
│   ├── board.routes.js      # Rutas para /boards
│   ├── list.routes.js       # Rutas para /lists
│   └── task.routes.js       # Rutas para /tasks
│
├── .env                     # Variables de entorno
├── index.js                 # Archivo principal, inicia el servidor
├── package.json
└── README.md

Tecnologías backend:
- Express (con módulos ES6)
- PostgreSQL
- pg para conexión y consultas SQL
- dotenv para variables de entorno
- cors configurado para producción
- Estructura modular y ordenada para escalar
