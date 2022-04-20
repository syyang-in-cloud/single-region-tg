[![pre-commit](https://github.com/ibm-xaas/dev-env/actions/workflows/pre-commit.yaml/badge.svg?branch=main)](https://github.com/ibm-xaas/dev-env/actions/workflows/pre-commit.yaml)
[![Docker](https://github.com/ibm-xaas/dev-env/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/ibm-xaas/dev-env/actions/workflows/docker-publish.yml)

# single region tg


## PREP

Please install the items below:
* docker
* docker-compose

## How to run
```
$ export IBMCLOUD_API_KEY=<YOUR IBMCLOUD_API_KEY>
$ docker-compose pull
$ docker-compose run single-region-tg
```
