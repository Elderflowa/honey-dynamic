<img
  src="https://raw.githubusercontent.com/Elderflowa/honey-dynamic/refs/heads/main/icons/icon.png"
  alt="Honey Icon"
  width="56"
  height="56"
/>

# honey-dynamic — a fork of honey
[![Docker Image Version (latest semver)](https://img.shields.io/docker/v/elderflowa/honey-dynamic?label=elderflowa%2Fhoney-dynamic%3Alatest)](https://hub.docker.com/r/elderflowa/honey-dynamic)

**honey-dynamic** is a fork of dani3l0's [Honey](https://github.com/dani3l0/honey) that provides a sleek, simple dashboard for your services.
It has cool animations, and with the small adjustments i made, sligthly more dynamic.

## Screenshot
| Configuration Page                                                                             |
| ---------------------------------------------------------------------------------------------- |
| <img src="https://raw.githubusercontent.com/Elderflowa/honey-dynamic/refs/heads/main/example.png" alt="Configuration" /> |
---
## Running in Docker
### Clone
Clone this repository:
```
git clone https://github.com/Elderflowa/honey-dynamic
cd honey-dynamic
```
### Customize
Change configuration if you like in `./config/config.json`.
If you wish to use your own icons or upload, place them in `./icons/example.png`, and reference them in the `config.json` as `/img/custom/example.png`.

### Run the container
```
docker compose up -d
```
## More information
Take a look at dani3l0's [original repository](https://github.com/dani3l0/honey).
