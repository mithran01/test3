FROM caddy:2.5.2
COPY Caddyfile /etc/caddy/
COPY src/index.php /var/www/html/
EXPOSE 80
EXPOSE 9000