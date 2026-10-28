# E4O-sitio

Sitio de la marca personal **E4O · Experience for Owners**.

Publicado en: https://charlysec-code.github.io/E4O-sitio/

## Cómo se trabaja

- Cada cambio llega como una **solicitud de cambios** (Pull Request).
- El sitio solo cambia cuando la aceptás (**Merge**).
- Si después no te gusta, la deshacés con **Revert**, sin rehacer nada.

## Volver atrás un cambio (desde Safari)

1. Entrá a https://github.com/charlysec-code/E4O-sitio/pulls?q=is%3Aclosed
2. Abrí la solicitud que querés deshacer.
3. Bajá hasta el final y tocá **Revert**.
4. En la solicitud nueva que se abre, tocá **Create pull request** y después **Merge pull request**.
5. En uno o dos minutos el sitio vuelve a como estaba.

## Puntos de restauración

Las versiones aprobadas se guardan como ramas que empiezan con `version-`:

| Versión | Qué incluye |
| --- | --- |
| `version-v1.0` | Manual de marca v2.0, header estilo Apple, buscador y mejoras de accesibilidad |

Para volver a una de ellas, pedíselo a Claude: "volvé a la v1.0".
