#!/bin/bash

# PM (28.02.2024) made script Windows-read
# CRLF to LF
# also using "bin/sh" as shebang lead to a "Bad substitution" error in line starting with "COMMAND"
# @see https://stackoverflow.com/a/20616103/2652918
# @see https://stackoverflow.com/a/23277604/2652918

# export DIR_TARGET="$1"
# COMMAND="${@:2}"
# docker-compose \
#   -f docker-compose.yaml \
#    run -e "DIR_TARGET=$DIR_TARGET" --rm tasks "$COMMAND"

# @see https://hub.docker.com/_/php
# @see https://www.sarulabs.com/post/1/2016-01-12/create-a-php-command-based-on-docker.html
# @see https://docs.docker.com/reference/cli/docker/compose/run/

docker-compose \
  -f docker-compose.yaml \
   run --rm helpers php $@
