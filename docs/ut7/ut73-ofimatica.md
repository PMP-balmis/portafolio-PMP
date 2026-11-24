# Documentación técnica y herramientas ofimáticas

## ¿Qué es la documentación técnica?

La **documentación técnica** es el conjunto de documentos que explican cómo se instala, configura, usa o repara un sistema. Debe ser clara, ordenada y reproducible: otra persona tiene que poder seguir los pasos y obtener el mismo resultado.

## Tipos de documentos técnicos

| Documento | Para qué sirve | Ejemplo |
| --------- | -------------- | ------- |
| Manual de usuario | Explica cómo usar un programa o equipo | Guía de uso de una impresora |
| Manual de instalación | Detalla los pasos para instalar y configurar | Instalación de Docsify |
| Inventario | Lista los equipos y componentes | Hoja de cálculo con los PC del aula |
| Informe de incidencias | Registra un fallo y su solución | Fallo de red y cómo se resolvió |
| Presupuesto | Detalla costes de equipos o servicios | Montaje de un equipo nuevo |

## Herramientas ofimáticas

| Herramienta | Uso principal | Opción privativa | Opción libre |
| ----------- | ------------- | ---------------- | ------------ |
| Procesador de textos | Manuales, memorias, informes | Microsoft Word | LibreOffice Writer |
| Hoja de cálculo | Inventarios, presupuestos, gráficos | Microsoft Excel | LibreOffice Calc |
| Presentaciones | Exposiciones | Microsoft PowerPoint | LibreOffice Impress |
| Editor Markdown | Documentación ligera y versionable | Typora | Visual Studio Code |

## Documentar con Markdown

Markdown es un lenguaje de marcas ligero: se escribe en texto plano y se convierte a HTML. Es el formato que usa Docsify. Así se escribe una página sencilla:

````markdown
# Título de la página

## Sección

1. Primer paso
2. Segundo paso

| Columna A | Columna B |
| --------- | --------- |
| Dato 1    | Dato 2    |

```bash
echo "bloque de código"
```
````

## Buenas prácticas al documentar

- Usa títulos y secciones para que se pueda leer en diagonal.
- Explica cada paso con comandos reales y su resultado.
- Añade capturas de pantalla solo cuando aporten información.
- Cita las fuentes que hayas consultado.
- Guarda los documentos con Git para tener el historial de cambios.

?> **Consejo:** Markdown se versiona con Git, se ve igual en cualquier equipo y se puede exportar a PDF desde el navegador.

!> **Atención:** un documento técnico que no se puede reproducir paso a paso no cumple su función. Prueba tus propias instrucciones antes de darlas por buenas.
