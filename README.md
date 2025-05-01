# DragAndList

**Drag & List** es una aplicación de gestión de tareas estilo Trello, construida con React, Vite, Express y PostgreSQL. Permite crear tableros, listas y tareas con funcionalidad de **drag & drop** entre listas usando `dnd-kit`.

---

##  Demo en Producción

🔗 **Frontend**: [https://dragandlist.netlify.app](https://dragandlist.netlify.app)  
🔗 **Backend (API)**: [https://dragandlist-backend.onrender.com](https://dragandlist-backend.onrender.com)

---

## 🧰 Tecnologías utilizadas

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



## 📁 Estructura del repositorio
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

