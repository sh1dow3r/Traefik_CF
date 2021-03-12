FROM traefik:1.7-alpine
ADD ./traefik.toml /etc/traefik/traefik.toml
COPY ./certs /etc/traefik/certs
ENV  CLOUDFLARE_EMAIL=l33t@gmail.com                   
ENV CLOUDFLARE_API_KEY=111111111111111111111111111111111111  
EXPOSE 80
EXPOSE 8080
EXPOSE 443
