# La isla del algoritmo 🏴‍☠️

Juego de pensamiento computacional para alumnos de 2.º de ESO. El alumnado crea una secuencia de instrucciones para que un pirata encuentre un tesoro y esquive las rocas.

## Jugar

[**Abrir el juego en GitHub Pages**](https://bitschips.github.io/tesoro_pirata_pensamiento_computacional_1/) (requiere activar GitHub Pages).

1. Escoge un número de pasos entre 1 y 9 y pulsa **Andar pasos** para añadir esa instrucción.
2. Añade **Girar izquierda**, **Girar derecha**, **Coger tesoro** o **Parar**. Cada clic añade una línea al algoritmo.
3. Utiliza las flechas **↑** y **↓** para ordenar las instrucciones o **✕** para eliminarlas.
4. Pulsa **Ejecutar** para que el pirata realice toda la secuencia, o **Paso a paso** para comprobar una instrucción por pulsación.
5. Cuando te equivoques, cambia el algoritmo y prueba de nuevo.

El pirata empieza en la esquina inferior izquierda y mira a la derecha. **Girar** cambia su orientación sin desplazarlo. **Andar** avanza en la dirección a la que está mirando. Para ganar debe llegar al cofre y ejecutar **Coger tesoro**.

## Objetivos didácticos

- Diseñar y ejecutar algoritmos secuenciales.
- Entender la diferencia entre desplazamiento y orientación.
- Detectar errores, corregirlos y volver a ejecutar.
- Comparar el número de instrucciones, intentos y desplazamientos.

## Tecnología

Toda la aplicación está contenida en `index.html`: HTML, CSS y JavaScript con dibujos pixel art mediante Canvas. Sin dependencias, sonido ni servidor.

## Activar GitHub Pages

1. Ir a **Settings → Pages**.
2. En **Build and deployment**, elegir **Deploy from a branch**.
3. Seleccionar **main** y **/(root)**, y guardar.
4. Abrir https://bitschips.github.io/tesoro_pirata_pensamiento_computacional_1/ cuando GitHub termine la publicación.

**Versión 1.0:** un nivel, instrucciones por clic, ejecución automática y paso a paso. No incluye condicionales ni bloques arrastrables.
