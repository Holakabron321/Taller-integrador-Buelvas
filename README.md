# Taller Integrador — Auditoría y Corrección de Sitio Web

**Autor:** Samuel Buelvas
**Curso:** Buenas Prácticas de Desarrollo de Software

## Tabla de hallazgos

| Defecto encontrado | Por qué era un problema | Cómo lo corrigió |
|---|---|---|
| Nombres de archivo con espacios y mayúsculas | Podía causar problemas con rutas/URLs y no seguía convención | Renombrados a `index.html` y `styles.css` |
| Variable `x` sin significado claro | No identificaba qué información representaba | Renombrada a `cantidadNotas` |
| Variables `a`, `b`, `c` sin significado claro | No indicaban qué nota representaba cada una | Renombradas a `nota1`, `nota2`, `nota3` |
| Variable `TempValue2` con nombre confuso | Sugería un valor temporal, pero almacenaba el resultado final | Renombrada a `promedio` |
| Función `calc()` con nombre poco descriptivo | No permitía saber qué operación realizaba | Renombrada a `calcularPromedio()` |
| IDs HTML poco descriptivos (`n1`, `n2`, `n3`, `r`, `r2`) | No explicaban qué representaba cada elemento | Renombrados a `nota1`, `nota2`, `nota3`, `resultadoPromedio`, `resultadoEstado` |
| Título de la página (`<title>pagina</title>`) | No describía el contenido del sitio | Cambiado a `Calculadora de Promedio` |
| Código innecesario (`data1` sin usar, `calcularAntiguo` comentada, `console.log`) | No cumplía ninguna función y ensuciaba el código | Eliminado por completo |

## Sitio publicado
[Enlace al sitio publicado en Netlify]

## Repositorio
[Enlace a este repositorio]