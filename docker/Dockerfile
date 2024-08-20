FROM docker:dind
ENV DOCKER_CLI_EXPERIMENTAL=enabled
RUN mkdir -p ~/.docker/cli-plugins
ADD https://github.com/docker/buildx/releases/download/v0.16.2/buildx-v0.16.2.linux-amd64 /root/.docker/cli-plugins/docker-buildx
RUN chmod a+x /root/.docker/cli-plugins/docker-buildx
