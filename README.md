# Into the Unknown — Releases

Downloadable client builds (Windows, Linux, Android, Web) and battle-host Docker images.

See **[Releases](https://github.com/gonczol92peter-code/Into_the_unknown_release/releases)** for versioned assets.

## Battle host quick start
```bash
gunzip -c 1935-authoritative-host-<version>.tar.gz | docker load
export BATTLE_DOCKER_IMAGE=1935-authoritative-host:<version>
docker compose -f deploy/hetzner-battle/docker-compose.battle.yml up -d
```
