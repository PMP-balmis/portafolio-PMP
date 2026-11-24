# Licencias de software

Una **licencia** es el contrato que define qué puedes hacer con un programa: usarlo, copiarlo, modificarlo o redistribuirlo.

## Tipos principales

| Tipo | Ejemplo | Código fuente | Coste |
| ---- | ------- | ------------- | ----- |
| Propietario | Windows, Microsoft Office | Cerrado | De pago |
| Libre (copyleft) | Linux (GPL) | Abierto | Normalmente gratuito |
| Libre (permisiva) | Apache, MIT | Abierto | Gratuito |
| Freeware | Adobe Reader | Cerrado | Gratuito |
| Shareware | WinRAR | Cerrado | Prueba y luego pago |

## Comprobar la licencia de un paquete

En Linux se puede consultar la licencia de un paquete instalado:

```bash
apt show nano | grep -i license
dpkg -L nano | grep copyright
```

> [!TIP]
> Antes de usar un programa en una empresa, comprueba siempre si su licencia permite uso comercial.

> [!WARNING]
> Usar software propietario sin licencia es ilegal (piratería) y puede acarrear sanciones.
