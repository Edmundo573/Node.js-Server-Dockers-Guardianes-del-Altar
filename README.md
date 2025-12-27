# 🌐 node-server-jwt-sqlite

Servidor Node.js con autenticación JWT y persistencia en SQLite.  
Un altar digital que combina técnica y ética: cada usuario accede con su llave secreta y sus tareas se guardan en piedra digital.

---

## 🚀 Características
- **Autenticación JWT**: cada usuario entra con su llave única.  
- **Persistencia en SQLite**: datos guardados con claridad y continuidad.  
- **Rutas modulares**: separación en `auth.js` y `tasks.js`.  
- **Guardianes del altar**: `.env` para llaves, `db.js` para conexión, `middleware` para protección.  
- **Documentación ética**: acompañado de `MANIFIESTO.md` como bandera de autonomía.

---

## 📂 Estructura del proyecto
# Node.js-Server-Dockers-Guardianes-del-Altar
node-server-jwt-sqlite/
├── index.js
├── package.json
├── routes/
│   ├── auth.js
│   └── tasks.js
├── models/
│   ├── users.js
│   └── tasks.js
├── middleware/
│   └── auth.js
├── db.js
├── README.md
├── MANIFIESTO.md
├── .gitignore
└── .env.example

Código

---

## ⚙️ Instalación
```bash
# Clonar el repositorio
git clone https://github.com/Edmundo573/node-server-jwt-sqlite.git

# Entrar al proyecto
cd node-server-jwt-sqlite

# Instalar dependencias
npm install

# Configurar variables de entorno
cp .env.example .env
# Edita .env con tu SECRET_KEY y configuración de base de datos
▶️ Uso
bash
# Iniciar servidor
npm start
Registro/Login → /auth/register, /auth/login

Gestión de tareas → /tasks (CRUD protegido por JWT)

🌱 Filosofía
Este proyecto no es solo código:

Es un altar digital que defiende la autonomía.

Cada commit es una semilla de claridad.

Cada README es una antorcha para la comunidad.

Cada manifiesto es un mapa ético.

📜 Licencia
Uso libre y comunitario.
El único compromiso: respetar la dignidad y la memoria viva.
