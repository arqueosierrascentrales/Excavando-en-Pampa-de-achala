# Excavando en Pampa de Altura

Juego de excavación arqueológica en primera persona, ambientado en un alero de granito de Pampa de Achala (Sierras Grandes de Córdoba, Argentina).

Excavás cuatro cuadrículas de 1 × 1 m por niveles artificiales de 5 cm. Las piezas se limpian con pincel, se registran y se levantan antes de seguir bajando, y el sedimento se cierne en zaranda. La libreta de campo y el plano de la excavación se descargan en PDF.

## Cómo jugar

| Acción | Computadora | Celular |
|---|---|---|
| Caminar | W A S D (Shift para apurar el paso) | Joystick a la izquierda |
| Mirar | Mouse (clic para fijar el puntero) | Arrastrar a la derecha |
| Usar herramienta | Clic (mantener para seguir) | Botón **Usar** |
| Cucharín / pincel / zaranda | 1 / 2 / 3 | Barra inferior |
| Agacharse | C | Botón **Agachar** |
| Libreta / colección | L / V | Barra inferior |

La regla de oro: si excavás por debajo de una pieza sin registrarla, se pierde su contexto.

La partida se guarda sola en el navegador de cada jugador.

## Publicarlo con GitHub Pages

GitHub está en inglés y no tiene la interfaz en castellano, así que al lado de cada paso va el nombre del botón tal como aparece en pantalla.

1. Entrá a https://github.com y creá una cuenta (**Sign up**). Si ya tenés, iniciá sesión (**Sign in**).
2. Arriba a la derecha tocá el signo **+** y elegí **New repository** (repositorio nuevo). En el nombre poné `pozo-nieve`, dejalo en **Public** (público) y tocá **Create repository** (crear repositorio).
3. En el repositorio, tocá **Add file** (agregar archivo) → **Upload files** (subir archivos). Arrastrá `index.html` y `README.md` y abajo tocá **Commit changes** (guardar cambios).
4. Arriba, entrá a **Settings** (configuración) y en el menú de la izquierda a **Pages**. En **Source** (origen) elegí **Deploy from a branch** (publicar desde una rama). En **Branch** (rama) elegí `main` y la carpeta `/ (root)` (raíz). Tocá **Save** (guardar).
5. Esperá uno o dos minutos y recargá la página. Arriba aparece el enlace del juego, con la forma `https://TU-USUARIO.github.io/pozo-nieve/`. Ese es el enlace que compartís.

Para actualizar el juego, volvé a **Add file → Upload files** y subí el `index.html` nuevo: reemplaza al anterior y el sitio se actualiza solo en un par de minutos.

## Requisitos técnicos

- Funciona en cualquier navegador actual con WebGL (Chrome, Firefox, Edge, Safari), en computadora o celular.
- Necesita conexión a internet para cargar las librerías desde cdnjs (three.js r128 y jsPDF 2.5.1) y las tipografías de Google Fonts.
- No usa servidor ni base de datos: es un único archivo `index.html`.

## Créditos y fuentes

- Puntas óseas, artefacto de hematita, fragmentos óseos decorados y pendiente de filita: fotografías de Rivero et al. (2024). **Antes de publicar el repositorio de forma abierta, conviene confirmar el permiso de uso de esas imágenes.**
- Materialidad lítica: Sario et al. (2022), *Relaciones de la Sociedad Argentina de Antropología* 47(1); Recalde (2009), *Anales de Arqueología y Etnología* 63-64.
- Cerámica de las Sierras de Córdoba: Figueroa, Pautassi y Dantas (2011), *ArqueoWeb* 13.

El sitio "Pozo Nieve", su estratigrafía y la distribución de hallazgos son ficticios y tienen fines didácticos.
