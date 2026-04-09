# Calculadora Interactiva

Proyecto web simple de una calculadora hecha con HTML, CSS y JavaScript.

## Vista general

Esta calculadora permite realizar operaciones basicas desde una interfaz visual:

- Suma (`+`)
- Resta (`-`)
- Multiplicacion (`*`)
- Division (`/`)
- Decimales (`.`)
- Limpieza de pantalla (`C`)

El resultado se muestra en pantalla al presionar `=`.

## Estructura del proyecto

- `index.html`: estructura de la interfaz (pantalla y botones).
- `style.css`: estilos visuales y ajustes responsivos.
- `script.js`: logica de la calculadora (entrada, limpieza y calculo).

## Como ejecutar

No necesitas instalar dependencias.

1. Descarga o clona este repositorio.
2. Abre `index.html` en tu navegador.
3. Usa los botones para escribir una operacion y presiona `=` para obtener el resultado.

## Tecnologias

- HTML5
- CSS3
- JavaScript (vanilla)

## Notas tecnicas

- El calculo se realiza actualmente con `eval()` dentro de `script.js`.
- Para un entorno de produccion, se recomienda reemplazar `eval()` por un parser seguro de expresiones.

## Posibles mejoras

- Soporte para teclado.
- Historial de operaciones.
- Manejo de errores mas detallado (por ejemplo, division por cero).
- Mejoras de accesibilidad (labels, foco visible y navegacion por teclado).

## Autor

Puedes agregar aqui tu nombre o usuario de GitHub.
