# Transferencia de ficheros

Para mover ficheros entre equipos por la red se usan distintos protocolos y herramientas.

## Protocolos de transferencia

| Protocolo | Puerto | Cifrado | Uso habitual |
| --------- | ------ | ------- | ------------ |
| FTP | 21 | No | Transferencias antiguas o en red local |
| FTPS | 990 | Sí (TLS) | FTP con cifrado |
| SFTP | 22 | Sí (SSH) | Transferencia segura de ficheros |
| SCP | 22 | Sí (SSH) | Copia rápida por línea de comandos |
| HTTP/HTTPS | 80 / 443 | Solo HTTPS | Descargas desde la web |

## Ejemplos con SFTP y SCP

```bash
# Conectarse por SFTP
sftp usuario@192.168.1.10

# Copiar un fichero local a un servidor
scp informe.pdf usuario@192.168.1.10:/home/usuario/

# Descargar un fichero del servidor
scp usuario@192.168.1.10:/home/usuario/informe.pdf .
```

?> **Consejo:** para sincronizar carpetas grandes usa `rsync`, que solo copia lo que ha cambiado.

!> **Atención:** FTP envía el usuario, la contraseña y los datos **sin cifrar**. Usa SFTP o FTPS siempre que sea posible.
