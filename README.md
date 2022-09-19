# ora2pg-docker
Dockerfile for running **ora2pg** based on https://github.com/darold/ora2pg

For documentation on running **ora2pg** see https://ora2pg.darold.net/

Running Examples:
- Get the version: `docker run --rm -it caffeine01/ora2pg --version`
- Map an `ora2pg.conf` located in current directory: `docker run --rm -it -v "$(pwd):$(pwd)" -w "$(pwd)" caffeine01/ora2pg --conf ./ora2pg.conf`
