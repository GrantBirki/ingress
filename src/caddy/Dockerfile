FROM caddy/caddy:2.8.4-alpine

# RUN apk add curl

RUN mkdir /app
COPY start.sh /app/start.sh

COPY Caddyfile /etc/caddy/Caddyfile

CMD ["sh", "/app/start.sh"]
