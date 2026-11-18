# Curso de HTML y CSS

Ejercicios y prácticas de mi aprendizaje de desarrollo web front-end.

Cada carpeta es un tema independiente con su propio `index.html` y su hoja de estilos. No hay dependencias ni proceso de compilación: HTML y CSS puros, abribles directamente en el navegador.

## Cómo verlo

```bash
git clone https://github.com/Omar3012-git/Curso-HTML-y-CSS.git
```

Después, doble clic en cualquier `index.html`. Si usas VS Code, la extensión **Live Server** recarga los cambios al guardar, que va mejor para los temas de animación y de diseño responsive.

## Contenido

### `HTML/` — Estructura y semántica

Fundamentos en la raíz: `parrafos_y_encabezados.html`, `listas.html`, `img.html`, `rutas.html` y `forms.html`.

Temas con carpeta propia:

| Tema | Qué cubre |
|---|---|
| `enlaces/` y `Enlaces (avanzado)/` | Navegación entre páginas, anclas, enlaces externos |
| `imágenes/` | Inserción de imágenes y rutas |
| `Picture source y media/` | Imágenes adaptativas con `<picture>` |
| `Atributos SRCSET y SIZES/` | Selección de resolución según el viewport |
| `Lazy loading/` | Carga diferida de imágenes |
| `Audio y video/` | Multimedia embebido |
| `Tablas/` | Tablas de datos |
| `Textarea y labels/` | Formularios accesibles |
| `Details y Summary/` | Contenido plegable nativo |
| `Comentarios metatags y favicons/` | Metadatos del documento |

### `CSS/` — Presentación y maquetación

**Fundamentos** — Selectores, Selectores avanzado, Cascadas y especificidad, Colores, Unidades de medida

**Modelo de caja** — Box sizing, Width y height, Padding y margin, Bordes, Outline, Display, Overflow y control de flujo de texto

**Maquetación** — Position relative y absolute, Fixed y sticky, Holy Grail
- `Flexbox/` — Alineación · Flex direction, wrap y flow · Flex basis, shrink y grow
- `Grid/` — Grid explícito e implícito · Grid column y row · Grid area · Grid gap · Repeat y minmax · Grid flow dense · Subgrid · Grid dinámico y responsive

**Estilo visual** — Fondos, Gradientes, Sombras, Propiedades de texto (con fuentes Montserrat locales), Pseudoclases, Pseudoelementos

**Diseño responsive** — Media queries, Container queries, Feature queries, Bloques y multimedia flexible, Imágenes y vídeos adaptativos

**Animación** — Transitions, Animaciones, Rango de animaciones, Animaciones en página, Animaciones con scroll, Botones animados, Typewriter, Ventana modal

### `Ejercicios/` — Prácticas completas

- **Primer página web** — Portfolio de una página («Barista Édgar»): cabecera con perfil, sección de skills, galería de proyectos en grid y formulario de contacto.
- **Tarjetas de perfil** — Componente de tarjeta reutilizado en varias variantes de color.

## Estado

Repositorio de aprendizaje en curso. El código prioriza entender cada concepto por separado antes que la reutilización entre carpetas, así que es normal encontrar estilos repetidos de un tema a otro.
