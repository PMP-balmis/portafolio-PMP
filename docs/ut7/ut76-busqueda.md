# Búsqueda y fiabilidad de documentación técnica

Saber buscar y comprobar si una fuente es fiable es esencial para documentar bien.

## Operadores de búsqueda

| Operador | Qué hace | Ejemplo |
| -------- | -------- | ------- |
| `"..."` | Busca la frase exacta | `"error 0x80070005"` |
| `site:` | Limita a una web | `site:learn.microsoft.com powershell` |
| `filetype:` | Busca un tipo de fichero | `filetype:pdf manual raid` |
| `-` | Excluye una palabra | `docker -desktop` |
| `OR` | Una u otra palabra | `ssh OR sftp` |

## Ejemplo de búsqueda avanzada

```
site:docs.github.com "GitHub Pages" filetype:html
```

## Criterios para valorar una fuente

| Criterio | Pregunta |
| -------- | -------- |
| Autoría | ¿Quién lo escribe y qué credenciales tiene? |
| Actualidad | ¿Cuándo se publicó o actualizó? |
| Origen | ¿Es documentación oficial, un foro o un blog? |
| Contraste | ¿Otras fuentes confirman lo mismo? |

?> **Consejo:** prioriza la **documentación oficial** del fabricante o del proyecto antes que foros o blogs.

!> **Atención:** no copies comandos de internet sin entenderlos. Un comando de un foro puede borrar datos o abrir una puerta de seguridad.
