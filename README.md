docker-moodle
=============

A Dockerfile that installs the Moodle 3.1 stable, Apache, PHP, MySQL and SSH


## Installation

```
git clone https://github.com/sergiogomez/docker-moodle.git
cd docker-moodle
docker build -t moodle .
```

## Usage

To spawn a new instance of Moodle:

```
docker run --name moodle1 -e VIRTUAL_HOST=moodle.domain.com -d -t -p 80 -p 22 moodle
```

You can visit the following URL in a browser to get started:

```
http://moodle.domain.com/moodle
```
Forked from [sergiogomez](https://github.com/sergiogomez/docker-moodle). Thanks.

Thanks to [eugeneware](https://github.com/eugeneware) and [ricardoamaro](https://github.com/ricardoamaro) for their Dockerfiles.
