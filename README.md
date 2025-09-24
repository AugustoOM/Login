# Login responsive (HTML/CSS)

Ejemplo de pantalla de ingreso:
- En móviles: el formulario ocupa el 100% y se centra.
- En escritorio: el formulario queda alineado a la derecha y usa ~30% del ancho.

## Cómo usar
1. Abre `index.html` en tu navegador.
2. Si utilizas VSCode, puedes usar la extensión Live Server para auto-recargar.

## Decisiones / Justificación
- HTML semántico (`main`, `section`, `form`, `label`) para accesibilidad.
- CSS puro (sin frameworks) para simplicidad.
- Layout con CSS Grid en `.page`:
  - Desktop (`min-width: 992px`): `grid-template-columns: 1fr 30vw`; el `1fr` deja espacio vacío a la izquierda y el formulario se alinea a la derecha.
  - Móviles: una sola columna para que el formulario ocupe el 100%.
- Estados de foco visibles, tamaños cómodos y buen contraste.

---
Autor: Tú
