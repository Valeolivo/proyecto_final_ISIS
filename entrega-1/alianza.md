# Alianza con el equipo de Backend

Proyecto: P1 – Plataforma de autoaprendizaje digital (Sala de Internet del CLENA).
Repositorio de Backend: [Autoaprendizaje-digital---Clena](https://github.com/MarcusRambal/Autoaprendizaje-digital---Clena)

Aplicación desplegada: [autoaprendizaje-digital-clena.vercel.app](https://autoaprendizaje-digital-clena.vercel.app)

## 1. Backlog validado

Tablero de GitHub Projects del equipo de Backend: [Backlog – Autoaprendizaje digital CLENA](https://github.com/users/MarcusRambal/projects/15/views/1)

<img src="img/Captura%20de%20pantalla%202026-11-10%20222231.png" alt="Backlog priorizado en GitHub Projects" width="700">

La prioridad de las historias se acordó con el Product Owner de Backend. Quedaron 12 historias «Debe tener» y 1 «Debería tener» (US-P1-12).

## 2. Sprint Review

| Fecha | Sprint | Grabación | Asistentes de nuestro equipo |
|---|---|---|---|
| 2026-11-10 | Sprint #3 (ÚLTIMA PRESENCIAL) | [Ver grabación en OneDrive](https://1drv.ms/f/c/3c37f21d2002ab70/IgCfukmQ7kPhQZvkKz8Dp2XWAXMMmGi_u7-kFRV86Aj3HO0?e=MrJohY) | Valeria Olivo Cantillo, Valery Romero Mendoza, Luciana Díaz Mariano, Matías Vásquez Terán |

**Retroalimentación que dimos:**
- Validamos que lo construido en este sprint cumple con nuestras historias de usuario y sus criterios de aceptación.
- Consideramos que la interfaz es intuitiva y fácil de recorrer, lo cual es clave para el público de la Sala de Internet, especialmente los adultos mayores.
- Presentamos la aplicación en el CLENA y tuvo muy buena acogida por parte de las personas que la conocieron.

## 3. Prueba del incremento: Issues de feedback

Probamos como usuarios la versión desplegada el 2026-11-09 y registramos los hallazgos como Issues con la etiqueta `feedback-cliente`.

| Issue | Historia revisada | Qué esperábamos | Qué pasó | Autor |
|---|---|---|---|---|
| [#34](https://github.com/MarcusRambal/Autoaprendizaje-digital---Clena/issues/34) | US-P1-01 | Dado que escribo «naveg» en el buscador, cuando presiono Buscar, entonces aparece «Navegación segura en internet» entre los resultados. Dado que abro una guía, cuando presiono «Descargar PDF», entonces obtengo un PDF con el título, la categoría y el contenido. |  La búsqueda encuentra la guía escribiendo solo una parte del título y el PDF se descarga con el contenido de la guía. El criterio se cumple. | Valeria Olivo Cantillo |
| [#35](https://github.com/MarcusRambal/Autoaprendizaje-digital---Clena/issues/35) | US-P1-04 | Al enviar el formulario con nombre, asunto y descripción, ver un mensaje de que la solicitud fue recibida. | Aparece la confirmación y la solicitud queda registrada como pendiente. Sugerimos que el mensaje indique qué pasa después. | Valeria Olivo |
| [#37](https://github.com/MarcusRambal/Autoaprendizaje-digital---Clena/issues/37) | US-P1-09 | Que las categorías nuevas aparezcan en los filtros públicos, que haya aviso si el nombre ya existe y que no se pueda eliminar una categoría con guías asociadas sin reasignarlas. | Las categorías se guardan y aparecen en los filtros; los avisos de duplicado y de restricción al eliminar funcionan. Sugerimos agrandar los textos de las alertas. | Luciana Díaz  |
|  [#38](https://github.com/MarcusRambal/Autoaprendizaje-digital---Clena/issues/38) | US-P1-10 | Que un usuario creado con rol Staff entre a su panel, que haya aviso de error si el correo ya está registrado y que solo se puedan elegir los roles Staff o Público. | El usuario Staff accede al panel correcto, el correo duplicado se bloquea y el menú de roles solo muestra Staff y Público. Sugerimos un botón para mostrar u ocultar la contraseña. | Luciana Díaz  |
| [#40](https://github.com/MarcusRambal/Autoaprendizaje-digital---Clena/issues/40) | US-P1-11 | Poder crear una cuenta aceptando el aviso de privacidad, iniciar sesión y ver el menú según el rol, recibir un mensaje claro con contraseña equivocada y volver al inicio al cerrar sesión. | El registro, el inicio de sesión por rol, el manejo de contraseña errónea y el cierre de sesión funcionan y cumplen los criterios. Sugerimos validar el formato del correo mientras se escribe. | Matías Vásquez  |

## 4. Estado de avance de las historias «Debe tener»

Estado tomado del tablero de Backend el AAAA-MM-DD.

| Historia | Descripción | Estado |
|---|---|---|
| US-P1-01 | Consultar catálogo de guías | To Do |
| US-P1-02 | Realizar lecciones de práctica | To Do |
| US-P1-03 | Consultar mi progreso | To Do |
| US-P1-04 | Solicitar ayuda al staff | To Do |
| US-P1-05 | Eliminar mi cuenta y datos personales | To Do |
| US-P1-06 | Gestionar guías y lecciones | To Do |
| US-P1-07 | Gestionar solicitudes de ayuda | To Do |
| US-P1-08 | Consultar estadísticas | To Do |
| US-P1-09 | Gestionar categorías | To Do |
| US-P1-10 | Crear usuarios | To Do |
| US-P1-11 | Registrarme e iniciar sesión | To Do |
| US-P1-13 | Ajustar accesibilidad | To Do |
