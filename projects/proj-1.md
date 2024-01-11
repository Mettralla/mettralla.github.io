---
layout: post
title: 'Mi Biblioteca'
---

<p>
    <img alt="HTML" src="https://img.shields.io/badge/HTML-E34F26.svg?logo=html5&logoColor=white">
    <img alt="CSS" src="https://img.shields.io/badge/CSS-1572B6.svg?logo=css3&logoColor=white">
    <img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-7952B3.svg?logo=bootstrap&logoColor=white">
    <img alt="Python" src="https://img.shields.io/badge/Python-3776AB.svg?logo=python&logoColor=white">
    <img alt="Django" src="https://img.shields.io/badge/Django-092E20?logo=django&logoColor=green">
    <img alt="SQLite" src ="https://img.shields.io/badge/SQLite-003B57.svg?logo=sqlite&logoColor=white">
</p>


{% include image.html url="https://github.com/Mettralla/WebApp" image="projects/proj-1/thumbnail.jpg" %}

Junto a un grupo de programadores desarrollé una aplicación web utilizando el framework Django para una biblioteca, permitiendo el registro de libros, socios y empleados. Implementé un sistema completo de CRUD para autores, libros, socios y empleados, con la capacidad de listar y restaurar registros inactivos. Además, se incluyó un CRUD para préstamos de libros.

La aplicación cuenta con una API que permite visualizar todos los libros ofrecidos y consultar el detalle de un libro específico a través de endpoints específicos. Se integró el uso de Bases de Datos SQLite, el ORM de Django y Jinja2 como sistema de templates, con estilos aplicados mediante Bootstrap.

En el panel de administración de Django, se habilitaron búsquedas por nombre de libro, así como por nombre y apellido para socios, autores y empleados. Todo el proyecto está documentado en un archivo README, detallando los pasos para ponerlo en marcha y resaltando las funcionalidades disponibles. El código del proyecto se encuentra en un [repositorio en GitHub](https://github.com/Mettralla/WebApp).
