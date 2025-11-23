<div align="center">
  <br />
    <img src="./assets/images/icon.png" alt="Balu Logo" width="100"/>
  <br />

  <h1>Balu - Real Estate App</h1>

  <p>
    <strong>Tu puerta de entrada al hogar perfecto.</strong>
  </p>

  <p>
    Una aplicación móvil moderna de bienes raíces construida con <strong>React Native</strong>, diseñada para ofrecer una experiencia fluida en la búsqueda de propiedades.
  </p>

  <p align="center">
    <a href="#-tech-stack">Tecnologías</a> •
    <a href="#-features">Características</a> •
    <a href="#-getting-started">Comenzar</a> •
    <a href="#-screenshots">Galería</a>
  </p>
</div>

<hr />

## 📖 Sobre el Proyecto

**Balu** es una plataforma inmobiliaria nativa desarrollada para facilitar la compra y renta de propiedades. Utilizando la potencia de **Expo** y el estilizado rápido de **NativeWind**, junto con un backend robusto en **Appwrite**, Balu ofrece actualizaciones en tiempo real, autenticación segura y una interfaz de usuario intuitiva.

## 🛠 Tech Stack

Este proyecto utiliza las últimas tecnologías del ecosistema React Native:

- **Core:** [React Native](https://reactnative.dev/) con [Expo SDK 52](https://expo.dev/)
- **Lenguaje:** [TypeScript](https://www.typescriptlang.org/)
- **Estilos:** [NativeWind](https://www.nativewind.dev/) (Tailwind CSS)
- **Navegación:** [Expo Router](https://docs.expo.dev/router/introduction/)
- **Backend & Auth:** [Appwrite](https://appwrite.io/)
- **Fuentes:** Google Fonts (Rubik)

## ✨ Características Principales

* ✅ **Autenticación Segura:** Inicio de sesión con Google OAuth integrado vía Appwrite.
* ✅ **Exploración de Propiedades:** Feed de inicio con propiedades destacadas y recomendaciones.
* ✅ **Búsqueda Avanzada:** Filtrado por categorías (Casa, Departamento, etc.) y búsqueda por texto.
* ✅ **Detalle de Inmuebles:** Vista detallada con imágenes, ubicación y características.
* ✅ **Perfil de Usuario:** Gestión de cuenta y avatar personalizado.

## 📱 Capturas de Pantalla

<div align="center">
  <img src="./assets/images/onboarding.png" alt="Onboarding" width="200"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./assets/images/home-placeholder.png" alt="Home Screen" width="200"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./assets/images/details-placeholder.png" alt="Details" width="200"/>
</div>

## 🚀 Comenzar (Getting Started)

Sigue estos pasos para correr el proyecto localmente.

### Prerrequisitos

- Node.js instalado.
- Dispositivo físico con **Expo Go** o un Emulador (Android Studio / Xcode).

### Instalación

1.  **Clonar el repositorio**
    ```bash
    git clone [https://github.com/ashrahx/balu.git](https://github.com/ashrahx/balu.git)
    cd balu
    ```

2.  **Instalar dependencias**
    ```bash
    npm install
    ```

3.  **Configurar Variables de Entorno**
    Crea un archivo `.env` en la raíz del proyecto y agrega tus credenciales de Appwrite (basado en `.env.example`):

    ```env
    EXPO_PUBLIC_APPWRITE_ENDPOINT=[https://cloud.appwrite.io/v1](https://cloud.appwrite.io/v1)
    EXPO_PUBLIC_APPWRITE_PROJECT_ID=tu_project_id
    EXPO_PUBLIC_APPWRITE_DATABASE_ID=tu_database_id
    EXPO_PUBLIC_APPWRITE_GALLERIES_COLLECTION_ID=tu_collection_id
    EXPO_PUBLIC_APPWRITE_REVIEWS_COLLECTION_ID=tu_reviews_id
    EXPO_PUBLIC_APPWRITE_AGENTS_COLLECTION_ID=tu_agents_id
    EXPO_PUBLIC_APPWRITE_PROPERTIES_COLLECTION_ID=tu_properties_id
    EXPO_PUBLIC_APPWRITE_BUCKET_ID=tu_bucket_id
    ```

4.  **Ejecutar la aplicación**
    ```bash
    npx expo start
    ```

## 📂 Estructura del Proyecto
