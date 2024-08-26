# [RAISE](https://raisetools.github.io/) Tools

Docker image containing [RSLTC](https://github.com/raisetools/rsltc) and [SML](https://www.smlnj.org/).

## Getting started

1. Download, install and run Docker from https://docs.docker.com/get-docker/
2. Build and start container with `docker-compose up -d --build`.

At this point you're good to go if you want to use VSCode for coding and running commands.

## Running commands manually

Attach to the container with `docker-compose exec rsl bash`. This opens an interactive `bash` shell inside the container that allows you to use the `rsltc` and `sml` commands.

When you're done, exit the shell and stop the container with `docker-compose down`.
