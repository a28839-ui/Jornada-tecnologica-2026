  # Jornada-tecnologica-2026
Tarea Git Hub App Web
# Jornada Tecnológica Vila-real 2026

Web informativa responsive para la Jornada Tecnológica Local 2026 usando **Bootstrap 5**.

## 🎨 Secciones y Grid Bootstrap

| Sección | Clases Bootstrap | Columnas |
|---------|------------------|----------|
| Navbar | `navbar-expand-lg` | 12 |
| Hero | `row align-items-center` | col-lg-6 x2 |
| Programa | `row g-4` | **col-lg-4 x3** (12 columnas) |
| Ponentes | `row g-4` | **col-lg-6 x2** (12 columnas) |
| Footer | `row` | col-md-6 x2 |

## 🧩 Componentes Bootstrap usados
- Navbar responsive
- Cards (sección programa)
- Grid system completo
- Utility classes (py-5, mb-4, text-center, etc.)

## 📝 Historial Commits

1. **Inicial**: Estructura carpetas + README
2. **Navbar+Hero**: Estructura principal implementada
3. **Sección Programa**: Primer grid obligatorio (12 columnas)
4. **Sección Ponentes+Footer**: Segundo grid + cierre proyecto

## 🐛 Mayor dificultad encontrada
**Problema**: Navbar no colapsaba correctamente en móvil.  
**Solución**: Revisé `data-bs-target="#navbarNav"` y corregí ID del collapse.

![Captura final](./CAPTURAS/web-completa.png)
