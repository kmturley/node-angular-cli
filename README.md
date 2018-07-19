# node-angular-cli

Docker image for sites which need to build/run:

* NodeJS 8.x
* Angular Cli
* Chrome (testing)

## Installation

    docker build -t "kmturley:node-angular-cli" .

## Usage

Within your own Dockerfile:

    FROM: kmturley/node-angular-cli

Within a CI pipeline:

    image: kmturley/node-angular-cli

## Contact

For more information please contact kmturley
