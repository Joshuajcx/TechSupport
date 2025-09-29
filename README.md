# 🛠️ TechSupport  

Aplicación móvil desarrollada en **React Native** con **MongoDB** como base de datos.  
TechSupport permite a los usuarios **reportar incidencias**, **dar seguimiento a tickets** y **conectarse con técnicos de soporte** de manera sencilla desde Android o iOS.  

---

## 🚀 Características principales  
- 📱 **Login y registro** de usuarios con autenticación segura  
- 📝 Creación, asignación y seguimiento de **tickets de soporte**  
- 🔔 Notificaciones en tiempo real (Firebase)  
- 👨‍💻 Panel para técnicos con estado de incidencias  
- 🌐 Disponible para **Android e iOS**  

---

## 🛠️ Tecnologías utilizadas  

### 🔹 Frontend  
![React Native](https://img.shields.io/badge/React%20Native-61DAFB?logo=react&logoColor=white)  
![React Navigation](https://img.shields.io/badge/Navigation-React%20Navigation-blue?logo=reactrouter)  
![AsyncStorage](https://img.shields.io/badge/Storage-AsyncStorage-lightgrey)  

### 🔹 Backend  
![Node.js](https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=white)  
![Express](https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white)  

### 🔹 Base de datos  
![MongoDB](https://img.shields.io/badge/Database-MongoDB-green?logo=mongodb&logoColor=white)  

### 🔹 Otras herramientas  
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)  
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)  
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)  
![VSCode](https://img.shields.io/badge/Editor-VSCode-007ACC?logo=visualstudiocode&logoColor=white)  

---

## 📸 Capturas de pantalla  

> *(Agrega imágenes de la app para mostrar su interfaz: login, tickets, dashboard…)*  

| Login | Dashboard | Ticket |
|-------|-----------|--------|
| ![Login](./screenshots/login.PNG) | ![Dashboard](./screenshots/Dashboard.PNG) | ![Ticket](./screenshots/ticket.PNG) |


---

## ⚙️ Instalación y configuración  

1. Clonar este repositorio:  
   ```bash
   git clone https://github.com/TU_USUARIO/TechSupport.git
   cd TechSupport
2. Instalar dependencias:
  ```bash
   npm install
   #o
   yarn install
3. Configurar variables de entorno:
   Crea un archivo .env en la raíz con:
   ```bash
   PORT=3000
   MONGO_URI=mongodb://localhost:27017/
   JWT_SECRET=
   
4. Iniciar la app en Android:
   ```bash
   npx react-native run-android
   #O en iOS:
   npx react-native run-ios
