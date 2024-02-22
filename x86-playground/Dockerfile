FROM debian:bullseye

RUN apt-get update -y && apt-get install -y \
  build-essential \
  gdb \
  nasm \
  vim \
  clang \
  make

RUN groupadd -g 1000 devuser && useradd -r -u 1000 -g devuser devuser
USER devuser
WORKDIR /usr/devuser

