# Clasificación y licencias de software

## ¿Qué es el software?

El **software** es el componente lógico de un ordenador: el conjunto de programas, datos e instrucciones que hacen que el hardware realice tareas útiles. Sin software, el hardware no sirve para nada.

## Clasificación según su finalidad

| Tipo | Función | Ejemplos |
| ---- | ------- | -------- |
| Software de sistema | Gestiona el hardware y da servicio a los demás programas | Windows, Linux, macOS, controladores |
| Software de aplicación | Permite al usuario realizar tareas concretas | LibreOffice, Firefox, VLC |
| Software de desarrollo | Sirve para crear otros programas | Visual Studio Code, compiladores, Git |
| Software malicioso (malware) | Daña o espía el sistema sin permiso del usuario | Virus, ransomware, troyanos |

## ¿Qué es una licencia?

Una **licencia de software** es el contrato entre el autor y el usuario que define qué se puede hacer con el programa: usarlo, copiarlo, modificarlo o redistribuirlo.

## Tipos de licencias

| Licencia | Código fuente | Coste | Modificar y redistribuir | Ejemplo |
| -------- | ------------- | ----- | ------------------------ | ------- |
| Propietaria (privativa) | Cerrado | Normalmente de pago | No permitido | Windows, Microsoft Office |
| Libre con copyleft | Abierto | Libre | Sí, manteniendo la misma licencia | Linux (GPL) |
| Libre permisiva | Abierto | Libre | Sí, con pocas condiciones | Apache, MIT, BSD |
| Freeware | Cerrado | Gratuito | No permitido | Adobe Reader |
| Shareware | Cerrado | Prueba y luego pago | No permitido | WinRAR |
| Dominio público | Abierto | Gratuito | Sin restricciones | SQLite |

## Las 4 libertades del software libre

1. **Libertad 0:** ejecutar el programa para cualquier propósito.
2. **Libertad 1:** estudiar cómo funciona y adaptarlo a tus necesidades.
3. **Libertad 2:** distribuir copias.
4. **Libertad 3:** mejorar el programa y publicar las mejoras.

## Consultar la licencia de un paquete en Linux

Se puede comprobar la licencia de un programa instalado desde la terminal:

```bash
# Ver información del paquete
apt show nano

# Ver el fichero de copyright con la licencia
cat /usr/share/doc/nano/copyright
```

En Windows, la licencia de Windows se puede comprobar con:

```
slmgr /dli
```

?> **Consejo:** antes de usar un programa en una empresa, comprueba siempre que su licencia permite el uso comercial.

!> **Atención:** usar software propietario sin licencia es ilegal (piratería) y puede acarrear sanciones. Además, el software crackeado suele incluir malware.
