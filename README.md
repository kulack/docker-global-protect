# Docker container for GlobalProtect

Originally cloned from https://github.com/bhaskarkc/docker-global-protect on Jan 21, 2023.

## Steps to build

- `docker build -t gp .`
- ```sh
  docker run --privileged -it \
      -e SERVER=<globalprotect-host-url> \
      -e USER=<username> \
      -e PASSWORD=<password> \
      gp
  ```
