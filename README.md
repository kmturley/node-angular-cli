# node-angular-cli

Docker image for sites which need to build/run:

* NodeJS 8.x
* Angular Cli 6.x
* Chrome (testing)

## Installation

    docker build -t "kmturley:node-angular-cli:node8-angular6" .

## Usage

Within your own Dockerfile:

    FROM: kmturley/node-angular-cli:node8-angular6

Within a CI pipeline:

    image: kmturley/node-angular-cli:node8-angular6

## Contact

For more information please contact kmturley
