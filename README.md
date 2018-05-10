# Nginx reverse proxy

Dockerized Nginx reverse proxy and served via HTTPS using free Let's Encrypt certificates. New sites can be added on the fly by just modifying docker-compose.yml and then running docker-compose up as the main Nginx config is automatically updated and certificates (if needed) are automatically acquired.


This can be a fairly simple way to have easy, reproducible deploys for websites with free, auto-renewing TLS certificates.
