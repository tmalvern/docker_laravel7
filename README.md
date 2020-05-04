# docker_laravel7
A laravel 7 development environment
## Requirements

- Docker
- Docker-compose

## Usage

1. Clone this repository

```
git clone git@github.com:kenneth-hendricks/docker_moodle.git docker_moodle
```

2. Clone Moodle code into siteroot

```
cd docker_moodle
git clone git@github.com:moodle/moodle.git siteroot
```

3. Copy site config across

```
cp moodle/moodle-config siteroot/config.php
```

4. Start containers

```
docker-compose up
```
