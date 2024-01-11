---
layout: post
title: 'Discord Clone'
---

<p>
    <img alt="HTML" src="https://img.shields.io/badge/HTML-E34F26.svg?logo=html5&logoColor=white">
    <img alt="CSS" src="https://img.shields.io/badge/CSS-1572B6.svg?logo=css3&logoColor=white">
    <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?logo=javascript&logoColor=black">
    <img alt="Python" src="https://img.shields.io/badge/Python-3776AB.svg?logo=python&logoColor=white">
    <img alt="Flask" src="https://img.shields.io/badge/Flask-3776AB.svg?logo=flask&logoColor=white">
    <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1.svg?logo=mysql&logoColor=white">
    <img alt="Insomnia" src="https://img.shields.io/badge/Insomnia-6f00ff?logo=insomnia&logoColor=white">
</p>


{% include image.html url="https://github.com/Mettralla/discord-clone-backend" image="projects/proj-3/thumbnail.jpg" %}

Desarrollé una aplicación web de mensajería similar a Discord, empleando Flask como backend y MySQL como base de datos. La interfaz, construida con HTML, CSS y JavaScript, permite a los usuarios registrarse, iniciar sesión y participar en servidores, canales y chats.

La aplicación presenta un diseño de tres columnas para la visualización de servidores, canales y mensajes. Se incorporaron funciones para crear servidores, canales y mensajes, con restricciones de modificación y eliminación exclusivas para el creador del contenido.

Además, se implementó un componente de perfil de usuario que permite la actualización de datos personales, incluyendo la imagen del usuario. Se desarrollaron manejadores de errores personalizados y se gestionó la sesión de usuario, restringiendo el acceso a los endpoints de la API REST solo a usuarios autenticados.

El buscador de servidores permite a los usuarios encontrar servidores por nombre, mostrando información relevante sobre cada resultado. Se añadió la capacidad de gestionar notificaciones e invitaciones a servidores.

El proyecto se encuentra dividido en dos repositorios diferentes: uno para el [frontend](https://github.com/Mettralla/discord-clone-frontend) y otro para el [backend](https://github.com/Mettralla/discord-clone-backend). Las instrucciones para montar ambos están detalladas en el README de cada repositorio.
