# Contribuir

¿Conoces o has construido una herramienta que encaje aquí? Abre un PR que añada una fila a la tabla de su categoría, o un issue con el enlace. El mantenedor revisa cada propuesta con estos criterios.

## Criterios

Un proyecto entra si cumple todo esto:

1. **Es open source.** Tiene una licencia de código abierto reconocida. Un repo sin licencia no entra aunque el código sea público.
2. **Lo puede usar un agente.** Es una CLI, un servidor MCP, una skill, un bot, una API… Una extensión o una web pensada solo para personas no entra.
3. **Está vivo.** Ha tenido actividad en los últimos 12 meses y no está archivado.

## Formato

Copia esta fila y cambia `usuario`, `repo`, la licencia, la descripción y el tipo:

```markdown
| [**repo**](https://github.com/usuario/repo) | <img src="https://github.com/usuario.png?size=40" width="20" height="20" alt=""> [@usuario](https://github.com/usuario) | ![Estrellas](https://img.shields.io/github/stars/usuario/repo?style=flat-square&label=%E2%AD%90&color=f5c518) | ![Licencia](https://img.shields.io/badge/MIT-blue?style=flat-square) | Qué hace, en una frase. | `CLI` |
```

- Licencia: el identificador SPDX del repo (`MIT`, `GPL--3.0`; en shields.io un guion se escribe doble).
- Tipo: `CLI`, `MCP`, `skill`, `Bot`, `Home Assistant`, `App`, `API`, `Script`, `TUI` o `Agente`. Combínalos con `+`.
