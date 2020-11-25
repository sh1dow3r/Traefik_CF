# Traefik Cloudflare

## How to install:
### Generate Certificat for Traefik:

1- Clone the repo


`git clone https://github.com/sh1dow3r/Traefik_CF`

2- Generate the certificate


`cd Traefik_CF; mkdir -p certs; openssl req -x509 -newkey rsa:4096 -nodes -out certs/cert.crt -keyout certs/cert.key -days 365`

