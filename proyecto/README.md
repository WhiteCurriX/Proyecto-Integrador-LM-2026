# Historia del trap en España

## Datos del alumno

- **Nombre:** Curro Romero Diaz
- **Usuario de GitHub:** WhiteCurriX
- **Curso:** 1º DAM · Lenguajes de Marcas y Sistemas de Gestión de Información

## Tema elegido

Historia del trap en España.

## ¿Por qué lo he elegido?

He elegido el trap porque es un género que escucho y que ha cambiado mucho la música en español en pocos años. Quiero contar cómo llegó a España, cómo pasó de las escenas locales a ser música de masas y qué artistas fueron marcando cada etapa. Es un tema con mucho contenido, ideal para una web con varias páginas y para una lista de artistas con sus datos.

## Palabra del día UD5
DIA

**UD5:** DÍA

## UD3 · Estructura HTML

Cosas que le faltan a mi `index.html` según lo visto en clase:

1. El `head` no está completo: el `title` no sigue el formato `Inicio | Nombre del proyecto` y faltan las etiquetas `meta` de `description`, `keywords` y `author`.
2. El contenido no está organizado en bloques `div` con comentarios y no hay títulos `h3`, así que la jerarquía de títulos se queda corta.
3. No tiene separadores `hr`, cita `blockquote`, texto preformateado `pre`, entidades HTML ni pie de página con `&copy;`.

## Mapa del sitio

| Fichero | title | Qué contiene |
|---|---|---|
| index.html | Inicio \| Historia del trap en España | Portada: presentación, los pioneros (Kefta Boyz, PXXR GVNG, segunda generación), ficha de PXXR GVNG y mi opinión |
| historia.html | Historia \| Historia del trap en España | Las etapas del trap en España de 2013 en adelante y una cronología con las fechas clave |
| artistas.html | Artistas \| Historia del trap en España | Todos los artistas de `datos.xml` con su género, ciudad, año de inicio y años en activo |
| escena-actual.html | Escena actual \| Historia del trap en España | La nueva generación (Quevedo, Bad Gyal, Morad), el trap en los festivales y una reflexión personal |

### Validación en validator.w3.org

| Página | Errores del validador | Cómo los he corregido |
|---|---|---|
| index.html | 0 errores | No hizo falta corregir nada |
| historia.html | 0 errores | No hizo falta corregir nada |
| artistas.html | 0 errores | No hizo falta corregir nada |
| escena-actual.html | 0 errores | No hizo falta corregir nada |

## UD5 · Tablas y formularios

En `historia.html` voy a añadir una tabla con los momentos clave del trap underground en España, con el año, el artista, lo que pasó y la ciudad. Además crearé `contacto.html` con un formulario para que los visitantes me propongan artistas de la escena que todavía no aparecen en la web.

### POST frente a GET

He usado `method="post"` en el formulario de `contacto.html` porque envía datos personales como el correo o el teléfono, y con POST no aparecen en la URL ni se quedan guardados en el historial del navegador.

Así se vería el envío si usara GET:

`contacto.html?nombre=Curro&email=curro%40ejemplo.com&telefono=600123456&ciudad=barcelona&estilos=trap&origen=spotify&mensaje=Es+un+pionero+de+la+escena`

### Validación en validator.w3.org

| Página | Errores del validador | Cómo los he corregido |
|---|---|---|
| index.html | 0 errores | No hizo falta corregir nada |
| historia.html | 0 errores | No hizo falta corregir nada |
| contacto.html | 0 errores | No hizo falta corregir nada |

### Lo que he aprendido

En esta unidad he aprendido a hacer tablas accesibles con `caption`, `thead`, `tbody`, `tfoot` y `scope`, y a unir celdas con `rowspan` y `colspan` sin que se descuadre la tabla.
También he aprendido a montar formularios con `fieldset` y `legend`, a usar distintos tipos de controles y a relacionar cada `label` con su campo mediante el `id`.
Por último, he visto la diferencia entre enviar los datos con GET o con POST y cuándo conviene usar cada uno.
