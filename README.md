# node-angular-cli

Docker image for sites which need to build/run:

* NodeJS 10.x
* Angular Cli 8.x
* Chrome (testing)

## Installation

    docker build -t "kmturley:node-angular-cli:node10-angular8" .

## Usage

Within your own Dockerfile:

    FROM: kmturley/node-angular-cli:node10-angular8

Within a CI pipeline:

    image: kmturley/node-angular-cli:node10-angular8

## Contact

For more information please contact kmturley
