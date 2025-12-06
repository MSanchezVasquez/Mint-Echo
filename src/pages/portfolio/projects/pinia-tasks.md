---
layout: /src/layouts/ProjectLayout.astro
title: "Aplicación de lista de tareas con Vue 3, Vite y Pinia"
pubDate: 2025-10-21
description: "Aplicación de notas moderna, responsiva y eficiente creada con Vue 3."
languages: ["vue", "pinia",]
image:
  url: "/images/projects/pinia-tasks.webp"
  alt: "Captura de pantalla de la App de Pinia Tasks"
---

**Aplicación de lista de tareas con Vue 3, Vite y Pinia** Permite crear, marcar como favoritas, completar y eliminar tareas, además de persistirlas en un backend con **JSON Server** desplegado en Render.

## 🧩 Características Principales

- **Gestión completa de tareas**: Crear, completar, destacar como favoritas y eliminar tareas de forma rápida y eficiente.
- **Persistencia automática**: El estado se conserva en el navegador gracias a `pinia-plugin-persistedstate`, complementado con almacenamiento remoto..
- **Sincronización con backend**: Comunicación con una API REST en Render mediante operaciones `GET`, `POST`, `PATCH` y `DELETE` para mantener los datos actualizados.
- **Arquitectura modular**: Separación clara entre componentes, vistas y store, facilitando la escalabilidad y el mantenimiento del proyecto.
- **Interfaz moderna y reactiva**: Desarrollada con Vue 3 y la Composition API para asegurar rapidez y una experiencia de usuario fluida.
- **Despliegue en la nube**: Frontend hospedado en Netlify y backend en Render, permitiendo acceso desde cualquier dispositivo.
- **Actualizaciones parciales eficientes**: Uso de `PATCH` para modificar solo propiedades individuales como `favorite` o `completed`, optimizando el tráfico y el rendimiento.

## 💡 Tecnologías usadas

- [Vue 3](https://vuejs.org/)
- [Vite](https://vitejs.dev/)
- [Pinia](https://pinia.vuejs.org/) (gestión de estado)
- [pinia-plugin-persistedstate](https://prazdevs.github.io/pinia-plugin-persistedstate/)
- [JSON Server](https://github.com/typicode/json-server) (backend REST fake)
- Deploy: [Netlify](https://www.netlify.com/) + [Render](https://render.com/) (para el backend)

## 🌐 Demo y Código

Este proyecto fue parte de mi ruta de aprendizaje profundo sobre gestión de estados en frontend.

👉 [Ver código en GitHub](https://github.com/MSanchezVasquez/task-list-vue)

## 🎯 Objetivo

Ofrecer una aplicación simple, rápida y moderna para gestionar tareas desde el navegador, permitiendo crear, organizar y actualizar actividades de forma intuitiva, con persistencia local y sincronización con un backend basado en JSON Server.
