# traefik-mkcert-portainer

With this docker compose you can use Traefik in your localhost, just execute this command:

```bash
docker compose up -d
```

and edit `/etc/hosts`, adding your domains:
```env
# Standart host address
127.0.0.1  localhost
...
# Add this lines
127.0.0.1  portainer.localhost
127.0.0.1  traefil.localhost
```

Now, just access: `https://traefik.localhost` and `https://portainer.localhost`.
