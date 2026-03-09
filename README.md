# Jornada Tecnológica Vila-real 2026

## Descripción del proyecto
Web informativa responsive para la **Jornada Tecnológica Local 2026**, desarrollada con Bootstrap 5. Presenta el evento de forma clara y atractiva, con toda la información esencial: programa, ponentes destacados, ubicación y detalles prácticos.

## Secciones de la web y columnas Bootstrap usadas

| Sección | Clases Bootstrap | Columnas usadas |
|---------|------------------|-----------------|
| **Navbar** | `navbar-expand-lg` | 12 columnas completas |
| **Hero** | `row align-items-center` | `col-lg-6 x2` (12 columnas) |
| **Programa** | `row g-4` | `col-lg-4 x3` (12 columnas) |
| **Ponentes** | `row g-4` | `col-lg-6 x2` (12 columnas) |
| **Footer** | `row` | `col-md-6 x2` (12 columnas) |

## Componentes Bootstrap utilizados
- Navbar responsive con toggle para móvil
- Cards en la sección de programa
- Grid system completo (`container`, `row`, `col-*`)
- Utility classes (`py-5`, `mb-4`, `text-center`, etc.)

## Historial de commits
1. **Inicial**: Estructura de carpetas + README base
2. **Navbar+Hero**: Estructura principal implementada y responsive
3. **Sección Programa**: Primer grid obligatorio (12 columnas totales)
4. **Sección Ponentes+Footer**: Segundo grid obligatorio + cierre del proyecto

## Mayor dificultad encontrada
**Problema**: El navbar no colapsaba correctamente en móvil - el menú no aparecía al pulsar el botón hamburguesa.

**Solución**: Revisé el atributo `data-bs-target="#navbarNav"` en el botón toggle y corregí el ID del elemento `collapse`. Ahora funciona perfectamente en todas las resoluciones.

## Instalación y uso
1. Clona el repositorio:
```bash
git clone https://github.com/a28839-ui/Jornada-tecnologica-2026.git
