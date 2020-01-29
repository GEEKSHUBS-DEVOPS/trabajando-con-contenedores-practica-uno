#!/bin/bash

####################
###   Binaries   ###
####################
DOCKER_COMPOSE=$(which docker-compose)
####################

PROJECT_PATH="$( cd "$( dirname "${BASH_SOURCE[0]}" )" && cd .. && pwd )"

export USER_ID=${UID}
export GROUP_ID=${UID}

${DOCKER_COMPOSE} -f ${PROJECT_PATH}/deploy/develop/docker-compose.yaml run --user="$UID" microservice-a bash -c "lb4 ${@}";
