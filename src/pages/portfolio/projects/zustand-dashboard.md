---
layout: /src/layouts/ProjectLayout.astro
title: "Zustand Dashboard"
pubDate: 2025-12-11
description: "Aplicación de demostración profesional construida con React, TypeScript y Vite, diseñada para mostrar patrones avanzados de manejo de estado utilizando Zustand."
languages: ["react", "ts", "zustand"]
image:
  url: "/images/projects/zustand-dashboard.webp"
  alt: "Captura de pantalla de la App de zustand-dashboard"
---

Una aplicación de demostración profesional construida con **React, TypeScript y Vite**, diseñada para mostrar patrones avanzados de manejo de estado utilizando **Zustand**.

El proyecto simula un panel de administración completo con autenticación, tableros de tareas tipo Jira, formularios segmentados y persistencia de datos.

---

## 🧩 Características Principales

### 🔐 Autenticación y Seguridad

- **Auth Store:** Manejo de estado de sesión (Authorized/Unauthorized/Pending).
- **Protected Routes:** Uso de `DashboardLayout` como Guard para proteger rutas privadas.
- **Persistencia:** La sesión sobrevive a recargas de página (`persist` middleware).

### 📋 Tablero de Tareas (Kanban)

- **Drag & Drop Nativo:** Implementación de arrastrar y soltar tareas entre columnas.
- **Inmutabilidad con Immer:** Uso del middleware `immer` para actualizaciones de estado anidado complejas.
- **Interacciones UI:** Modales para creación (SweetAlert2) y confirmación de eliminación.

### 🍰 Patrón de Slices (Wedding Invitation)

- Demostración de cómo dividir un Store gigante en pequeñas partes lógicas (**Slices**).
- **Stores:** `PersonSlice`, `GuestSlice`, `DateSlice` combinados en un `useWeddingStore` único.

### 🐻 Contadores y Objetos (Bears & Person)

- Ejemplos básicos de contadores y manejo de objetos simples.
- Visualizadores de estado tipo "Terminal" para depuración en tiempo real.

---

## 💡 Tecnologías usadas

- **Core:** React 18, TypeScript, Vite.
- **Estado:** Zustand (con middlewares: `devtools`, `persist`, `immer`).
- **Estilos:** Tailwind CSS, Font "Plus Jakarta Sans".
- **Iconos:** React Icons (IO5).
- **Utilidades:** Classnames, UUID, SweetAlert2.

## 🌐 Demo y Código

Este proyecto fue parte de mi ruta de aprendizaje profundo sobre gestión de estados en frontend.

👉 [Ver código en GitHub](https://github.com/MSanchezVasquez/notes-app)

## 🧠 Conceptos de Zustand Aplicados

1.  **Store Creation:** Creación de stores tipados con TypeScript.
2.  **Middlewares:**
    - `persist`: Para guardar datos en LocalStorage/SessionStorage.
    - `devtools`: Para conexión con Redux DevTools.
    - `immer`: Para mutar estado de forma "inmutable" y sencilla.
3.  **Custom Hooks:** Separación de lógica de UI (ej. `useTasks`).
4.  **Slices Pattern:** Composición de stores grandes a partir de piezas pequeñas.
