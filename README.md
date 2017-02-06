[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/db-rotator.svg)](https://hub.docker.com/r/rubygem/db-rotator/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/db-rotator.svg)](https://hub.docker.com/r/rubygem/db-rotator/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/db-rotator.svg)](https://hub.docker.com/r/rubygem/db-rotator/)
[![Gem Downloads](https://img.shields.io/gem/dt/db-rotator.svg)](https://rubygems.org/gems/db-rotator/)
# db-rotator

Auto-Generated Docker image for db-rotator to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/db-rotator`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/db-rotator`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/db-rotator`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/db-rotator/)
