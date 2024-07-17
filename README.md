# wireguard + traefik + authelia
Docker Compose stack to deploy wireguard VPN server with [wg-easy](https://github.com/wg-easy/wg-easy), [traefik](https://github.com/traefik/traefik) as reverse proxy to access wg-easy UI and [authelia](https://github.com/authelia/authelia) for authentication.

## Deploy
- Get duckdns token and export below environmental varaibles
```bash
$ export MY_PROVIDER="duckdns"
$ export MY_DOMAIN=""
$ export DUCKDNS_TOKEN=""

$ docker-compose up -d
```
