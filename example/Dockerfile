# Example base image
FROM debian:buster

# Install your dependencies
RUN apt-get update && \
	apt-get install -y lolcat

WORKDIR /repo

ENTRYPOINT ["tool-name"]

# TODO: Adjust command to run benchmark
CMD ["--help"]
