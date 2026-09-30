# Learning

Mis apuntes de todo lo que voy aprendiendo en el camino a ser desarrolladora de software: arquitectura, bases de datos, DevOps, seguridad, IA y más. Cada nota explica un tema con mis propias palabras, con diagramas y ejemplos de código.

> [!IMPORTANT]
> **Este repositorio está pensado para abrirse con [Obsidian](https://obsidian.md).** GitHub muestra el texto y los diagramas, pero los callouts, los checkboxes personalizados y los enlaces entre notas solo se ven bien dentro de Obsidian.

## Cómo abrirlo en Obsidian

1. Cloná el repositorio:
   ```bash
   git clone https://github.com/checorazza/learning
   ```
2. En Obsidian, elegí **Open folder as vault** y seleccioná la carpeta clonada.
3. Cuando Obsidian pregunte si confiás en el autor del vault, elegí **Trust author and enable plugins**. Si no aparece el aviso, andá a *Settings → Community plugins* y hacé clic en **Turn on community plugins**.

El tema **AnuPpuccin** y el plugin **Style Settings** ya vienen incluidos en el repositorio, con sus ajustes. El paso 3 es necesario para que Style Settings aplique esos ajustes; sin él, el tema se ve con los valores por defecto.

Los diagramas están hechos con [Mermaid](https://mermaid.js.org), que Obsidian renderiza sin plugins extra.

## Índice

- **[DevOps](devops/)**
  - [Docker](devops/docker.md)
  - [Feature flags](devops/feature-flags.md)
- **[Fundamentos](fundamentos/)**
  - [Patrones de diseño](fundamentos/patrones-de-diseno.md)
  - [Principios SOLID](fundamentos/solid.md)
- **[IA / LLMs](ia-llms/)**
  - [MCP (Model Context Protocol)](ia-llms/mcp.md)

## Convenciones de las notas

**Frontmatter.** Cada nota empieza con propiedades de Obsidian: `aliases`, `tags`, `categoria` y `created`.

**Callouts.** Bloques destacados según el tipo de contenido:

| Callout | Uso |
|---|---|
| `[!abstract]` | Resumen del tema al inicio de la nota |
| `[!example]` | Analogías y ejemplos |
| `[!question]` | El problema que resuelve un concepto |
| `[!quote]` | Definición original de un concepto, con su autor |
| `[!info]` / `[!note]` | Contexto o aclaraciones |
| `[!tip]` | Trucos y formas de recordar algo |
| `[!warning]` / `[!danger]` | Riesgos, errores comunes, seguridad |

**Checkboxes de AnuPpuccin.** Marcan el tipo de cada ítem en una lista:

| Sintaxis | Significado |
|---|---|
| `- [k]` | Punto clave |
| `- [p]` | Ventaja (pro) |
| `- [c]` | Desventaja (contra) |
| `- [i]` | Información |
| `- [?]` | Pregunta abierta |
| `- [I]` | Idea |

**Enlaces.** Los temas relacionados se enlazan con `[[wikilinks]]`. Un enlace a una nota que todavía no existe marca un tema pendiente de escribir.

**Diagramas.** Todos en Mermaid.
