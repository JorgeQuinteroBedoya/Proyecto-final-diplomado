# Rival Mind · Presentación del proyecto final

Presentación web de nueve diapositivas inspirada en la estructura de la PPTX de referencia y adaptada a la identidad vigente de Rival Mind. El contenido refleja el flujo actual: Jina Reader, análisis con Gemini, respaldo opcional con Groq y reglas locales como último recurso. También distingue las funciones implementadas de las que siguen pendientes y de las métricas que aún no se han medido.

## Abrir localmente

Abre `index.html` en un navegador. No necesita Node, instalación, conexión a servicios ni clave API.

## Controles

- Flechas izquierda y derecha, Page Up / Page Down o barra espaciadora para avanzar.
- Botones inferiores para anterior/siguiente.
- `F` o el botón ⛶ para pantalla completa.
- En celular, desliza a izquierda o derecha.
- `Ctrl + P` permite imprimir o guardar las diapositivas como PDF.

## Publicar en GitHub Pages

Sube esta carpeta completa al repositorio, conservando `index.html` y la carpeta `assets`. Configura Pages para publicar desde la rama y carpeta donde quede `index.html`. También puedes copiar el contenido de esta carpeta a la raíz de un repositorio dedicado.

La presentación es estática: las rutas de imágenes son relativas y no depende de APIs externas. Para mantenerla actualizada, revisa sus afirmaciones funcionales frente a la aplicación antes de publicar una nueva versión.

## Alcance y datos

El contenido describe capacidades del MVP; no presenta como resultados de negocio métricas que no se han medido. La prueba automatizada de cuatro marcas utiliza una fixture sintética, no una extracción real. El PDF que genera la aplicación incluye primero las fichas individuales y después la comparación consolidada. Cada ficha comienza en una página nueva y el contenido continúa en otra cuando lo requiere para conservar la legibilidad.
