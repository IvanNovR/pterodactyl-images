<h1 align="center">Pterodactyl Images</h1>

![GitHub License](https://img.shields.io/github/license/ivannovr/pterodactyl-images) [![Russian Readme](https://img.shields.io/badge/russian-readme-blue)](./README_RU.md)

Package registry: https://github.com/IvanNovR/pterodactyl-images/pkgs/container/pterodactyl-images

This repository provides Docker images intended for use with the Pterodactyl game server panel. The images package various runtimes prepared for running game servers and other services inside Pterodactyl containers.

## Supported platforms
- linux/amd64
- linux/arm64

## Available images

- [java](https://github.com/IvanNovR/pterodactyl-images/tree/main/java) ![Status](https://img.shields.io/github/actions/workflow/status/IvanNovR/pterodactyl-images/java.yml.svg)
  - standard &mdash; standard images follow the [Yolks](https://github.com/pterodactyl/yolks)-style layout and are intended as drop-in Java runtimes for Pterodactyl containers.
    - [8](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/8) &mdash; Image: [`ghcr.io/ivannovr/pterodactyl-images:java_8`](https://ghcr.io/ivannovr/pterodactyl-images:java_8)
    - [11](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/11) &mdash; Image: [`ghcr.io/ivannovr/pterodactyl-images:java_11`](https://ghcr.io/ivannovr/pterodactyl-images:java_11)
    - [17](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/17) &mdash; Image: [`ghcr.io/ivannovr/pterodactyl-images:java_17`](https://ghcr.io/ivannovr/pterodactyl-images:java_17)
    - [21](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/21) &mdash; Image: [`ghcr.io/ivannovr/pterodactyl-images:java_21`](https://ghcr.io/ivannovr/pterodactyl-images:java_21)
  - ca &mdash; CA images copy provided certificates into `/usr/local/share/ca-certificates/`, run the system CA update, and import those certs into the runtime truststore (for Java &mdash; the `cacerts` keystore) so applications trust the custom certificates.
    - [8](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/8-ca) &mdash; Image: [`ghcr.io/ivannovr/pterodactyl-images:java_8-ca`](https://ghcr.io/ivannovr/pterodactyl-images:java_8-ca)
    - [11](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/11-ca) &mdash; Image: [`ghcr.io/ivannovr/pterodactyl-images:java_11-ca`](https://ghcr.io/ivannovr/pterodactyl-images:java_11-ca)
    - [17](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/17-ca) &mdash; Image: [`ghcr.io/ivannovr/pterodactyl-images:java_17-ca`](https://ghcr.io/ivannovr/pterodactyl-images:java_17-ca)
    - [21](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/21-ca) &mdash; Image: [`ghcr.io/ivannovr/pterodactyl-images:java_21-ca`](https://ghcr.io/ivannovr/pterodactyl-images:java_21-ca)
