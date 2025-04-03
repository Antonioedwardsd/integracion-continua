# 📝 CI Pipeline API Project

Este proyecto es una API REST simple construida con **Node.js**, diseñada para gestionar usuarios. Incluye integración con **Docker** para facilitar la ejecución en contenedores y con **Jenkins** para automatizar flujos de integración y entrega continua (CI/CD).

> Repositorio original: [integracion-continua - GitHub](https://github.com/Antonioedwardsd/integracion-continua)

---

## 🚀 Características

- 📋 Listar todas los usuarios  
- 🔍 Obtener usuario por ID  

---

## ⚙️ Principales Tecnologías utilizadas

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Docker](https://www.docker.com/)
- [Jenkins](https://www.jenkins.io/)

---

## 💻 Cómo ejecutar el proyecto localmente

1. Clona el repositorio  
   ```bash
   git clone https://github.com/Antonioedwardsd/integracion-continua.git
   cd integracion-continua
   ```

2. Instalar dependencias: `npm install`  

3. Inicializar el servidor `npm start`

## Ejecutar el servidor

`node server.js`

## 🐳 Ejecutar con Docker

1. Construye la imagen del contenedor: `docker build -t task-api .`  

2. Ejecuta el contenedor: `docker run -p 3000:3000 task-api`

## 📂 Estructura del proyecto

integracion-continua/  
├── Dockerfile  
├── Jenkinsfile  
├── package.json   
├── app.js  
├── test/  
│   └── app.test.js  
├── db.json
├── server.js
├── README.md  
└── REPORT.md  

## 👩‍💻 / 👨‍💻 Equipo

- Antonio Edwards
- Eleazar Pina
- Igor Ianiszewski
- Rodrigo Rozas
- Tamara Bravo
