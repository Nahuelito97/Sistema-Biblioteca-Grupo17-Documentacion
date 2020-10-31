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

---

# HISTORIAS DE USUARIO NUEVAS A AGREGAR AL SISTEMA.

## HU3_Registrar Clientes.

### Actores Administrador

**Objetivo** Realizar el alta de clientes al sistema.

**como**: usuario administrador del sistema.

**quiero**: quiero poder cargar la informacion referente a un nuevo cliente.

**para**: poder tener un nuevo usuario cargado en el sistema y registrar sus alquileres de libros.

### Criterios de Aceptacion

- De completarse de manera exitosa la operacion, el sistema debe de mostrar un mensaje.
- Si el cliente ya se encuentra cargado en el sitema, debe de mostrarse un mensaje y se debe de cancelar la operacion.
- La informacion del cliente debe de estar completa para poder subirse, en caso contrario, se debe de mostrar un mensaje de alerta y cancelar la operacion.

---
## HU4_Registrar Usuarios.

### Actores Administrador

**Objetivo** Realizar el alta de usuarios(empleados o administradores) al sistema.

**como**: usuario administrador del sistema.

**quiero**: quiero poder cargar la informacion referente a un nuevo usuario.

**para**: poder tener un nuevo usuario Administrador o usuario Empleado en el sistema y asignarle algunos privilegios.

### Criterios de Aceptacion

- De completarse de manera exitosa la operacion, el sistema debe de mostrar un mensaje.
- Si el usuario ya se encuentra cargado en el sitema, debe de mostrarse un mensaje indicando que el usuario ya se encuentra registrado y se debe de cancelar la operacion.
- La informacion del usuario debe de estar completa para poder subirse, en caso contrario, se debe de mostrar un mensaje, y cancelar la operacion.



## HU5_Prestamos y Reservaciones.

### Actores Administrador/Cliente

**Objetivo** Realizar la operacion de prestamos de uno o varios libros

**como**: usuario administrador del sistema.

**quiero**: quiero poder asignarle libros a un cliente.

**para**: poder tener un libro asiciado a un presto y el prestamo a un cliente

### Criterios de Aceptacion

- De completarse de manera exitosa la operacion, el sistema debe de mostrar un mensaje.
- El libro debe de estar cargado en el sistema, estar diponible.
- El cliente que quiera alquilar este libro debe de estar registado, no debe de tener deudas o entregas de libros pendientes.   
- Solo se permitiran dos alquileres de ibros por cliente.
- La informacion del usuario debe de estar completa para poder subirse, en caso contrario, se debe de mostrar un mensaje, y cancelar la operacion.
