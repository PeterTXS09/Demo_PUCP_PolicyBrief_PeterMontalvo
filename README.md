# Claro — Demo de consentimiento informado

Demo estática en español. No requiere instalación, compilación ni servidor.

## Abrir
Abre `index.html` con un navegador. Conserva `styles.css` y `script.js` en la misma carpeta.

## GitHub Pages
1. Sube `index.html`, `styles.css` y `script.js` a la raíz de tu repositorio.
2. En la configuración del repositorio, abre Pages y elige publicar desde la rama que contiene los archivos, carpeta raíz.
3. Guarda y espera a que GitHub muestre el enlace publicado.

## Flujo
Cuenta con credenciales ficticias de solo lectura → términos → aceptación → tres preguntas aleatorias → confirmación simulada. Una respuesta incorrecta muestra el acuerdo correspondiente y permite reintentar. El resultado distingue los conceptos completados de los aciertos al primer intento.

## Personalizar
- `index.html`: estructura y marca.
- `styles.css`: diseño, colores, adaptación y animaciones.
- `script.js`: textos de términos (`clauses`) y banco de preguntas (`bank`). `correct` es el índice de la respuesta válida, empezando en cero; `c` enlaza la cláusula correspondiente.

## Datos
Sin backend, solicitudes de red desde JavaScript, cookies, localStorage, sessionStorage, analítica ni dependencias externas. Las respuestas solo existen en memoria y desaparecen al recargar. No se crea una cuenta real. Como cualquier alojamiento web, GitHub Pages puede gestionar registros técnicos propios ajenos a esta demo.

Los términos son ficticios; este prototipo no acredita consentimiento legal ni demuestra por sí solo comprensión real. Incluye navegación por teclado, diálogo de consulta y respeto a `prefers-reduced-motion`.
