# Manual de las Runas de Estilo
Casa Cannith - Biblioteca Perdida de Lady Elaydren

Trabajo Práctico N°6 – CSS  
Funcionamiento de los Sistemas Digitales - FSD 2026  
Prof. Roberto Argumedo
Estudiante: Agustín Bianchi
Curso: 4to Info
Fecha: 27/7/26
---

## De qué se trata

En este trabajo tuve que reconstruir la apariencia del Manual de las Runas de Estilo usando solo CSS. El HTML no se podía tocar, así que todo el diseño lo resolví desde el archivo style.css.

Cada tarjeta tenía que usar exclusivamente la técnica que le correspondía:
- La primera solo con Position
- La segunda solo con Flexbox
- La tercera solo con Grid

---

## Decisiones de diseño

Primero elegí una paleta de colores oscuros, con marrones, beige y dorados, para que se sienta como un pergamino antiguo y encaje con el estilo de la Casa Cannith.

En la estructura general usé Flexbox para acomodar el panel teórico al lado de cada tarjeta. Los números de las secciones (01, 02 y 03) los puse con position para que floten sobre el borde.

En la tarjeta de Position puse la imagen arriba ocupando todo el ancho y el contenido abajo. El badge de “Nivel 27” lo ubicé con position absolute en la esquina superior derecha y le di un poco de rotación para que se vea como una capa encima.

En la de Flexbox armé la tarjeta en horizontal: la imagen a la izquierda y el contenido a la derecha. Dentro del contenido también usé flex en columna para ordenar el título, la descripción, las estadísticas y las habilidades.

En la de Grid definí tres columnas. El título va arriba ocupando todo el ancho. Después en la segunda fila puse la imagen, la descripción y las estadísticas una al lado de la otra. Abajo dejé las habilidades y la información.

También agregué algunas mejoras visuales como sombras, un pequeño efecto hover y bordes más gruesos para que se vea más prolijo.

---

## Qué técnica me resultó más sencilla

La más fácil para mí fue Flexbox.

La disposición que pedía el mockup (imagen a un lado y el texto al otro) es justo para lo que sirve Flexbox. Con display: flex, flex-direction y gap se armó bastante rápido. No tuve que estar calculando posiciones ni áreas, se acomodó de forma bastante natural.

---

## Qué dificultades encontré

Lo más complicado fue respetar la regla de no mezclar técnicas. Varias veces me agarraba ganas de usar flex o grid en la tarjeta de Position y tenía que volver atrás.

La tarjeta de Grid me costó más. Coordinar bien las filas y columnas para que el título ocupe todo el ancho y las secciones de abajo queden alineadas como en el mockup me llevó varios intentos.

También me costó un poco ubicar bien el badge de la primera tarjeta. Tuvo que quedar arriba a la derecha, con rotación, y sin romper el resto del diseño.

Otro tema fue mantener el mismo estilo visual en las tres tarjetas aunque cada una estuviera hecha con una técnica distinta. Tuve que cuidar mucho los colores, bordes y tipografías para que no se vean desparejas.

---

## Cómo ver el proyecto

Solo hay que abrir el archivo index.html en el navegador.


Cambio1