**This repository is deprecated. Please use the vanilla Blaze image that can be found [here](https://github.com/samply/blaze) and add custom search parameters according to the [documentation](https://github.com/samply/blaze/blob/a451304c835036114cc2ec785feb5146d525d55b/docs/deployment/docker-deployment.md#custom-search-parameters).**

# CODEX Blaze

This repository contains a Blaze server image, which includes the search parameters necessary for the CODEX project.

The image is based on Blaze [v0.16](https://github.com/samply/blaze/releases/tag/v0.16).

## Start locally

`docker-compose up -d`

## Build manually

`docker build -t codex-blaze:0.16 .`

or using docker compose:

`docker-compose build`

## Initialise testdata

`bash init-testdata.sh`
