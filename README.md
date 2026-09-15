# Keycloak

`C:\Windows\System32\drivers\etc\hosts`

```
127.0.0.1 keycloak
```

```shell
docker compose -f https://raw.githubusercontent.com/vicziani/keycloak-training-2026-09-15/refs/heads/master/compose/docker-compose.yml up -d
```

```shell
docker compose -f https://raw.githubusercontent.com/vicziani/keycloak-training-2026-09-15/refs/heads/master/compose/docker-compose.yml --profile app up -d
```

```shell
docker compose -f https://raw.githubusercontent.com/vicziani/keycloak-training-2026-09-15/refs/heads/master/compose/docker-compose.yml --profile app down
```