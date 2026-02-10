# Simón dice: ¡GUAU! 🐶🔊✨

**Integrantes del Grupo 01** 🌟  
- Adrián Muñoz Lorenzo  
- Luis Gómez Del Moral  
- Sergio Alcántara Escudero  
- Coraima Mera Rodriguez  

## 1. Idea General 🎲

- **Género:** Puzzle / Memoria 🧠  
- **Plataforma:** PC / Web 💻🌐  
- **Público objetivo:** Casual / Infantil 👶😄  
- **Descripción:** El jugador debe repetir una secuencia de acciones realizadas por un perro guía. A medida que avanza, la secuencia se vuelve más larga y rápida. 🐕‍🦺➡️📈

## 2. Jugador 🧑‍🏫

- **Rol:** El jugador actúa como el dueño o entrenador del perro pixelado. 🐶❤️  
- **Objetivo:** Memorizar y ejecutar correctamente la secuencia de comandos para acumular la mayor puntuación posible (High Score) y desbloquear nuevas características estéticas. 🏆✨  
- **Habilidades requeridas:**  
  - Memoria a corto plazo: Para retener la secuencia de acciones que se acumulan ronda tras ronda. 🧠💭  
  - Reflejos: Para introducir los comandos dentro del tiempo límite antes de que la barra de progreso se agote. ⚡⌛  
  - Ritmo: Para mantener el multiplicador de "felicidad" activo respondiendo con fluidez. 🎶😊

## 3. Rondas 🔄

En cada ronda tendríamos en cuenta lo siguiente:  
- **Fase de Observación:** El perro realiza una serie de acciones (animaciones) de forma aleatoria. 👀🐕  
- **Fase de Entrada:** El jugador debe repetir la secuencia presionando las teclas asignadas. ✋⌨️  
- **Crecimiento:** Cada ronda ganada añade un paso nuevo a la secuencia actual. 📏➕

## 4. Mecánica del juego ⚙️

El núcleo del juego se basa en dos fases que se repiten en bucle:

1. **Fase de Observación** 👀  
   El juego ejecuta una serie de animaciones (ej: "¡Ladra, Salta, Siéntate!") 🗣️⬆️🪑

2. **Fase de Acción** ▶️  
   El jugador debe presionar las teclas correctas en el mismo orden.  
   Si fallas, el perro pone una animación de confusión. 😵‍💫🐶

## 5. Uso de Sprites 🖼️

| Característica       | Animación Utilizada              | Propósito en el Diseño                              |
|----------------------|----------------------------------|-----------------------------------------------------|
| Estado de Espera     | idlesprite.png                   | El perro respira y mueve la colita mientras espera que el juego empiece. 🐾😌 |
| Comando de Voz       | barksprite with lines.png        | Se usa cuando el comando requiere que el perro "ladre". 🗣️🔊 |
| Comando Físico       | jumpsprite.png                   | Ideal para comandos de "acción" o agilidad. ⬆️💨 |
| Modo Descanso        | sitsprite.png                    | Aparece entre rondas o cuando el jugador tarda mucho en responder. 🪑💤 |
| Final del Juego      | poopsprite.png                   | Una forma graciosa de decir "Game Over" si el jugador pierde la racha. 💩😂 |

## 6. Progresión y Recompensas 🚀

- **Multiplicador de "Felicidad":** Si el jugador responde muy rápido, el perro cambia de la animación walk a run para mostrar que está emocionado. 🏃‍♂️🐶😍  
- **Puntaje Máximo (High Score):** Guardar el récord de cuántos pasos logró recordar el jugador. 🏅📊  
- **Desbloqueables:** Por ejemplo, si llegas a la ronda 10, el perro puede ladrar con una animación diferente o cambiar de color mediante código. 🎨🔓

## 7. Feedback Visual y Sonoro 📢🎨

Es vital que el jugador sepa si lo está haciendo bien o mal, para eso tendremos en cuenta lo siguiente:

- **Acierto:** Si el jugador presiona la tecla correcta, el perro reproduce la animación de forma rápida y breve. ✅✨  
- **Error:** Si el jugador falla, puedes usar la animación "Sit" con un efecto de partículas de "humo" o signos de interrogación para mostrar confusión. ❓😖  
- **Tiempo Límite:** Añade una barra de progreso que baje lentamente; si no presionas la tecla antes de que se agote, el perro se distrae (puedes usar la animación "Poop" como un castigo divertido). ⏳💨😂

## 8. Interfaz 🖥️

En la interfaz planteada nos gustaría incorporar:

- **Menú principal:** Botón de jugar y salir. ▶️🚪  

- **Pantalla de juego:**  
  - Contador de Pasos: Un número grande que indique en qué paso de la secuencia vas (ej: 3/5). 🔢  
  - Puntuación máxima. 🏆  
  - Guía de Teclas: Un pequeño icono en pantalla que recuerde al jugador: [J] Ladrar, [K] Saltar, etc. ⌨️🪧  
  - Barra de Energía: Una barra que se llena con cada acierto y te da una "vida" extra si completas una secuencia perfecta. ❤️⚡

- **Game Over:** Un mensaje que diga ¡Oh, no! 😱
