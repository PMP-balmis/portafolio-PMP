# Correo y mensajería electrónica

El correo electrónico funciona con distintos **protocolos**: unos para enviar mensajes y otros para recibirlos.

## Protocolos de correo

| Protocolo | Función | Puerto estándar | Puerto seguro |
| --------- | ------- | --------------- | ------------- |
| SMTP | Enviar correo | 25 / 587 | 465 |
| POP3 | Descargar correo al equipo | 110 | 995 |
| IMAP | Consultar correo manteniéndolo en el servidor | 143 | 993 |

## Partes de una dirección

Una dirección como `usuario@dominio.es` se compone del **usuario** (antes de la `@`) y del **dominio** del servidor de correo (después).

## Comprobar la conexión a un servidor de correo

Se puede comprobar que un servidor IMAP responde de forma segura con:

```bash
openssl s_client -connect imap.gmail.com:993
```

Y comprobar los servidores de correo de un dominio con:

```bash
nslookup -type=MX gmail.com
```

?> **Consejo:** usa IMAP si accedes al correo desde varios dispositivos, porque los mensajes se quedan en el servidor.

!> **Atención:** desconfía de correos que piden datos personales o contraseñas (*phishing*). Comprueba siempre el remitente real y no abras adjuntos sospechosos.
