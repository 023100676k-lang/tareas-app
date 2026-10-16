# ✅ App de Tareas — React + Node.js Full-Stack

Aplicación full-stack de lista de tareas construida con React (frontend) y Node.js + Express (backend), desplegada en Vercel y Render.

## 🌐 URLs en producción

- **Frontend (Vercel):** https://tareas-app-xi.vercel.app
- **API REST (Render):** https://tareas-api-xx9h.onrender.com/api/tareas

## 🛠️ Tecnologías utilizadas

| Capa | Tecnología |
|---|---|
| Frontend | React 18 + Vite |
| Backend | Node.js + Express |
| Comunicación | API REST (HTTP + JSON) |
| Deploy Frontend | Vercel |
| Deploy Backend | Render |

## 📁 Estructura del proyecto

tareas-app/
├── client/ # Frontend React + Vite
│ ├── src/
│ │ ├── App.jsx
│ │ └── components/
│ └── package.json
└── server/ # Backend Node.js + Express
├── index.js
└── package.json

## 🚀 Ejecución local

### Requisitos
- Node.js v18 o superior
- npm

### Backend (Terminal 1)
cd server
npm install
npm run dev

### Frontend (Terminal 2)
cd client
npm install
npm run dev

## 📡 Endpoints de la API

| Método | Ruta | Descripción |
|---|---|---|
| GET | /api/tareas | Lista todas las tareas |
| POST | /api/tareas | Crea una tarea nueva |
| PUT | /api/tareas/:id | Marca/desmarca como completada |
| DELETE | /api/tareas/:id | Elimina una tarea |

## 👨‍💻 Autor

Diego Ninancuro Cárcamo — 023100676k@uandina.edu.pe
Curso: Plataformas para el Desarrollo de Aplicaciones — Semestre 2026-II
