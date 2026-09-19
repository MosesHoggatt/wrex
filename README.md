# Wrex

This repository is for **Wrex installers** and **Docker images**. Application source (Android, NAS, web) is private and is not published here.

## Docker images (server)

Friend installs pull these from GitHub Container Registry. Watchtower follows the `alpha` tag.

```
docker pull ghcr.io/moseshoggatt/wrex-http:alpha
docker pull ghcr.io/moseshoggatt/wrex-scanner:alpha
```

Version tags (example): `ghcr.io/moseshoggatt/wrex-http:0.1.0-alpha.1`

- **wrex-http** — website, APK download, media and catalog proxy
- **wrex-scanner** — library scan and transcode helper

Movie files and the catalog stay on the computer that runs Docker. They are not in these images.

If `docker pull` says denied, the package visibility is still private. The owner must set each package to **Public** on GitHub.

## Windows / Mac / Linux installer

Download builds from [Releases](https://github.com/MosesHoggatt/wrex/releases).