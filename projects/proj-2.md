---
layout: post
title: 'Disney World API'
---

<p>
    <img alt="Ruby" src="https://img.shields.io/badge/Ruby-EE0000?logo=ruby&logoColor=white">
    <img alt="Ruby on Rails" src="https://img.shields.io/badge/Ruby_on_Rails-EE0000?logo=rubyonrails&logoColor=white">
    <img alt="RSpec" src="https://img.shields.io/badge/RSpec-EE0000?logo=ruby&logoColor=white">
    <img alt="PostgreSQL" src ="https://img.shields.io/badge/PostgreSQL-4169E1.svg?logo=postgresql&logoColor=white">
    <img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white">
</p>

{% include image.html url="https://github.com/Mettralla/old_alkemy_challenge_disney_api" image="projects/proj-2/thumbnail.jpg" %}

Este proyecto se trata de una API basada en Ruby on Rails para explorar el cautivador universo de Disney. La API permite a los usuarios consultar y modificar información relativa a los personajes y películas que componen este mundo mágico, siguiendo el estándar REST en sus rutas.

Con el objetivo de salvaguardar la integridad y seguridad de la API, se implementó un sistema de autenticación de usuarios mediante tokens, adquiridos a través de los endpoints de registro y login.

La API proporciona una variedad de funcionalidades, incluyendo un listado de personajes con sus imágenes y nombres, operaciones CRUD (Creación, Edición y Eliminación) de personajes, detalles individuales de cada personaje con todos sus atributos y las películas o series asociadas. Además, se ha incorporado la capacidad de buscar personajes por nombre, edad, peso o películas/series en las que participaron.

La documentación del proyecto se llevó a cabo con Postman, facilitando la comprensión y consumo de la API. Como un elemento crucial para garantizar la calidad del código, se incorporaron tests utilizando RSpec, asegurando que la API funcione de manera fiable y libre de errores.

Todo el proyecto está documentado en un archivo README, detallando los pasos para ponerlo en marcha y resaltando las funcionalidades disponibles. El código del proyecto se encuentra en un [repositorio en GitHub](https://github.com/Mettralla/old_alkemy_challenge_disney_api).
