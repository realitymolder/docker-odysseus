# Odysseus Docker Image

Automated Docker image builds for [Odysseus](https://github.com/pewdiepie-archdaemon/odysseus) AI workspace.

## Image

```
docker.io/realitymolder/odysseus
```

## Tags

| Tag | Branch | Description |
|---|---|---|
| `stable` | `main` | Latest stable release |
| `YYYY-MM-DD` | `main` | Date-stamped stable release |
| `dev` | `dev` | Latest development build |
| `dev-YYYY-MM-DD` | `dev` | Date-stamped dev build |

## Usage

```bash
# Stable (production)
docker pull realitymolder/odysseus:stable

# Development (latest features)
docker pull realitymolder/odysseus:dev

# Specific date
docker pull realitymolder/odysseus:2026-06-20
```

## Build

Images are built automatically via GitHub Actions:

- **Push to `main`** → tagged as `stable` + date
- **Daily schedule (06:00 UTC)** → tagged as `dev` + date
- **Manual dispatch** → configurable branch and tag

## Links

- [Odysseus upstream](https://github.com/pewdiepie-archdaemon/odysseus)
- [Docker Hub](https://hub.docker.com/r/realitymolder/odysseus)
- [Unraid Templates](https://github.com/realitymolder/unraid-templates)
