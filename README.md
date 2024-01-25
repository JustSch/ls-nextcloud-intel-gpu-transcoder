# Nextcloud Intel GPU Transcoder

A docker mod that installs all the packages needed to use intel QuickSync Video (QSV) for transcoding using the linuxserver.io nextcloud image.
Use by adding the following environment variable to your container or docker-compose.yml:
```
DOCKER_MODS=ghcr.io/JustSch/ls-nextcloud-intel-gpu-transcoder
```

To use with other docker mods:
```
DOCKER_MODS=ghcr.io/JustSch/ls-nextcloud-intel-gpu-transcoder|MOD2|MOD3
```
