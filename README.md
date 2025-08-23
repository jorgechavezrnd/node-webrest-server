# Rest Web Server

## Generar certificados con OpenSSL

1. Para generar un certificado autofirmado con OpenSSL, puedes usar el siguiente comando:

```bash
openssl req -x509 -sha256 -nodes -days 365 -newkey rsa:2048 -keyout server.key -out server.crt
```

Esto generará dos archivos: `server.key` y `server.crt`, que son la clave privada y el certificado público, respectivamente.

2. Copiar los archivos generados a la carpeta `keys`.
