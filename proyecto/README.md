# SchoolMe - Plataforma Académica

SchoolMe es una plataforma académica diseñada para facilitar la gestión de tareas, usuarios y contenidos educativos dentro de una institución formativa. Permite a docentes y aprendices gestionar y visualizar actividades académicas en un entorno simple, seguro y accesible.

## Características principales

- Autenticación de usuarios (docentes, aprendices)
- Gestión de tareas académicas (CRUD)
- Visualización de tareas por estado
- Conexión entre frontend (Angular) y backend (Node/PHP/.NET según entorno simulado)
- Interfaz responsive con TailwindCSS o Bootstrap
- Manejo de errores global
- Pruebas unitarias e integración
- Control de versiones mediante Git y colaboración por ramas

## Cómo está organizado el proyecto

Este proyecto está dividido en carpetas para que sea más fácil de entender y trabajar. Cada parte tiene su función:

- **backend/**  Aquí está lo que hace que todo funcione por dentro. Es como el cerebro del proyecto.
- **frontend/**  Aquí están las pantallas que se ven, los botones y lo que usamos.
- **tests/**  Aquí probamos que todo esté funcionando bien.
- **docs/**  Aquí se guardan explicaciones de cómo hicimos las cosas.
- **README.md**  Este archivo que explica qué es SchoolMe y cómo está hecho.

##  Requerimientos Funcionales (cosas que debe hacer el sistema)

1. **Usuarios**
   - Crear usuarios (como profes o estudiantes).
   - Poder iniciar sesión con usuario y contraseña.
   - Revisar que los datos estén bien al ingresar.

2. **Tareas**
   - Crear nuevas tareas.
   - Ver la lista de tareas.
   - Cambiar o borrar tareas.
   - Mostrar solo las tareas que le tocan al usuario.

3. **Pantallas y botones**
   - Tener una pantalla principal con un menú.
   - Mostrar tareas por estado (pendiente, en proceso, terminada).
   - Tener un formulario para iniciar sesión.

4. **Conexión entre partes**
   - El frontend (pantallas) debe hablar con el backend (lógica).
   - Revisar que los datos estén bien antes de enviarlos.
   - Si algo falla, debe mostrar un mensaje.

5. **Seguridad**
   - Las partes del sistema deben protegerse para que solo entren los que tienen permiso.
   - Usar algo que revise si el usuario está conectado (como una llave).

6. **Pruebas**
   - Hacer pruebas para ver si las funciones funcionan bien.
   - Usar Postman para probar que las cosas se conectan bien.
   - Apuntar si hay errores y arreglarlos.

7. **Trabajo en equipo**
   - Usar ramas para trabajar por partes (como `feature/login`).
   - Revisar el trabajo antes de juntarlo.
   - Si hay problemas al juntar, resolverlos.

---

##  Requerimientos No Funcionales (cosas que ayudan a que funcione mejor)

1. **Seguridad**
   - Las contraseñas deben ir cifradas (como en clave).
   - Usar tokens (como pases especiales) para identificar al usuario.

2. **Facilidad de uso**
   - Que sea fácil de entender y usar.
   - Que se vea bien en computador y celular.

3. **Orden del código**
   - El código debe estar limpio y bien separado.
   - Que sea fácil de leer y modificar después.

4. **Crecer fácil**
   - Que se puedan agregar más cosas después (como notas, cursos, etc.).
   - Que no se rompa si le agregamos más módulos.

5. **Funciona en todos lados**
   - Que funcione en Chrome, Firefox, Edge.
   - Que también se vea bien en celulares.

6. **Velocidad**
   - Que cargue rápido.
   - Que no haga cosas innecesarias que lo hagan lento.




