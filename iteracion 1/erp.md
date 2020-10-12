# Sistema Libreria el mundo del lector

---

## Grupo

    1.Wagner Nahuel

---

## Visión

Desarrollaremos un sistema que permita a la biblioteca administrar la misma, recomendar libros, que permita al administrador poder generar nuevos usuarios, elminarlos, crear catalogos, realizar un alquiler de los libros que mas le agraden a los clientes, el administrador podra generar reportes.

---

## Lista de características

- Publicación de libros para reseñas.
- Clasificación de los libros según un género.
- Explorar catálogo.
- Reseña y puntuación de los libros.
- Recomendar libros a otros usuarios.
- Alquileres de libros segun los gustos de los usuarios.
- Gernerar nuevos usuarios, administradores.

---

## Análisis de dominio

La aplicación está dedicada en un contexto de administracion de todos los apectos de la biblioteca, asi mismo poder ralizar recomendaciones de libros, poder recomedar libros a otros usuarios.

---

## Bocetos interfaz gráfica

**Primera Interfaz**

![Inicio Sesion](/figuras/sesion.jpg)

**Segunda Interfaz**

    en esta vista podremos cargar la informacion referente a cada libro.

![Nuevo Libro](/figuras/nuevolibro.jpg)

---

**Tercera Interfaz**

    en esta vista podemos ver los catalogos que tenemos creados y realizar operaciones en ellos.

![Catalogo](/figuras/catalogo.jpg)

---

## Historias de usuario

---

### Actores del Sistema.

1. Usuario: el rol de usuario abarca las funciones básicas del sistema de administracion de la biblioteca, preguntar cuales son los libros mas leidos y mas llevados, poder alquilarlos.

2. Administrador: el rol de administrador se encarga de la parametrización del sistema (ABM de libros, catalogos, control de usuarios, creacion de nuevos usuarios, nuevos administradores morosos y géneros).

---

## HU1_Añadir libros

### Actores: Administrador

**como**: usuario administrador del sistema.

**quiero**: poder cargar informacion referente a un nuevo libro.

**para**: tener un nuevo libro cargado en la seccion de catalogos.

**Criterios de aceptacion**

- De completarse de manera exitosa la operacion, el sistema debe de mostrar un mensaje.
- Si el libro ya se encuentra cargado en el sitema, debe de mostrarse un mensaje y se debe de cancelar la operacion.
- La informacion del libro debe de estar completa para poder subirse, en caso contrario, se debe de mostrar un mensaje, y cancelar la operacion.

---

## HU2_Explorar Catálogo

### Actores: Administrador

**Objetivo**: Explorar el catálogo para observar nuevas publicaciones, libros disponibles.

**como**: usuario administrador del sistema.

**quiero**: ver una lista de catalogos y libros que estan disponibles.

**para**: poder recomendar a los usuarios de la biblioteca.

**Criterios de aceptacion**

- el catalogo debe de estar creado, y los libros agregados al mismo.

- los libros deben de estar disponibles, en caso contrario debe de mostrarse un mensaje de error

---

## Arquitectura

- Visual Studio Code
- git hub
- Html+Css+ JavaScript
- postman
- marckdow, para docuemtacion del proyecto
- Bostrap
