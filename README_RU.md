<h1 align="center">Pterodactyl Images</h1>

![Status](https://img.shields.io/github/actions/workflow/status/IvanNovR/JavaGameBox/maven.yml.svg) ![GitHub License](https://img.shields.io/github/license/ivannovr/pterodactyl-images) [![English Readme](https://img.shields.io/badge/english-readme-blue)](./README.md)

Репозиторий пакета: https://github.com/IvanNovR/pterodactyl-images/pkgs/container/pterodactyl-images

Этот репозиторий содержит Docker-образы, предназначенные для использования с панелью управления Pterodactyl. Образы упаковывают различные рантаймы, подготовленные для запуска игровых серверов и других сервисов внутри контейнеров Pterodactyl.

## Поддерживаемые платформы
- linux/amd64
- linux/arm64

## Доступные образы

- [java](https://github.com/IvanNovR/pterodactyl-images/tree/main/java) ![Status](https://img.shields.io/github/actions/workflow/status/IvanNovR/pterodactyl-images/java.yml.svg)
  - обычная &mdash; стандартные образы следуют [Yolks](https://github.com/pterodactyl/yolks) стилю оформлению и предназначены как готовые Java-рантаймы для контейнеров Pterodactyl.
    - [8](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/8) &mdash; Образ: [`ghcr.io/ivannovr/pterodactyl-images:java_8`](https://ghcr.io/ivannovr/pterodactyl-images:java_8)
    - [11](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/11) &mdash; Образ: [`ghcr.io/ivannovr/pterodactyl-images:java_11`](https://ghcr.io/ivannovr/pterodactyl-images:java_11)
    - [17](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/17) &mdash; Образ: [`ghcr.io/ivannovr/pterodactyl-images:java_17`](https://ghcr.io/ivannovr/pterodactyl-images:java_17)
    - [21](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/21) &mdash; Образ: [`ghcr.io/ivannovr/pterodactyl-images:java_21`](https://ghcr.io/ivannovr/pterodactyl-images:java_21)
  - ca &mdash; образы с CA копируют предоставленные сертификаты в `/usr/local/share/ca-certificates/`, обновляют системные CA и импортируют эти сертификаты в хранилище доверенных сертификатов рантайма (для Java &mdash; `cacerts`), чтобы приложения доверяли пользовательским сертификатам.
    - [8](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/8-ca) &mdash; Образ: [`ghcr.io/ivannovr/pterodactyl-images:java_8-ca`](https://ghcr.io/ivannovr/pterodactyl-images:java_8-ca)
    - [11](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/11-ca) &mdash; Образ: [`ghcr.io/ivannovr/pterodactyl-images:java_11-ca`](https://ghcr.io/ivannovr/pterodactyl-images:java_11-ca)
    - [17](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/17-ca) &mdash; Образ: [`ghcr.io/ivannovr/pterodactyl-images:java_17-ca`](https://ghcr.io/ivannovr/pterodactyl-images:java_17-ca)
    - [21](https://github.com/IvanNovR/pterodactyl-images/tree/main/java/21-ca) &mdash; Образ: [`ghcr.io/ivannovr/pterodactyl-images:java_21-ca`](https://ghcr.io/ivannovr/pterodactyl-images:java_21-ca)
