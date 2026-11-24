# Necesidades de software en entornos productivos

Cada entorno de trabajo necesita un conjunto de software distinto. Antes de instalar nada hay que analizar **qué tareas** se van a hacer y **qué requisitos** tiene cada programa (sistema operativo, memoria, licencia, compatibilidad).

## Software según el entorno

| Entorno | Necesidades principales | Ejemplos de software |
| ------- | ----------------------- | -------------------- |
| Oficina | Ofimática, correo, navegador, antivirus | LibreOffice, Thunderbird, Firefox |
| Diseño gráfico | Edición de imagen y vídeo, mucha RAM y GPU | GIMP, Inkscape, DaVinci Resolve |
| Desarrollo | Editor, control de versiones, compiladores | VS Code, Git, Node.js |
| Servidores | Sistema estable, servicios de red, copias de seguridad | Linux Server, Apache, MariaDB |
| Educación | Software libre, aplicaciones multiplataforma | Moodle, LibreOffice, Scratch |

## Listar el software instalado

Para hacer el inventario de software de un equipo:

```bash
# Windows (CMD o PowerShell)
winget list

# Linux (Debian/Ubuntu)
apt list --installed
dpkg -l | wc -l
```

?> **Consejo:** documenta siempre la versión de cada programa instalado. Facilita reproducir la instalación en otro equipo.

!> **Atención:** comprueba que el software elegido es compatible con el sistema operativo y que su licencia permite el uso en la empresa.
