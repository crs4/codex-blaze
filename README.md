# CODEX Blaze

This repository contains a Blaze server image, which includes the search parameters necessary for the CODEX project.

The image is based on Blaze [v0.14.0](https://github.com/samply/blaze/releases/tag/v0.14.0).

## Start locally

`docker-compose up -d`

## Build manually

`docker build -t codex-blaze:0.14.0 .`

or using docker compose:

`docker-compose build`

## Initialise testdata

`bash init-testdata.sh`
