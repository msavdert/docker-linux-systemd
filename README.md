# Docker Images with systemd

[![Build](https://github.com/msavdert/docker-rhel-systemd/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/msavdert/docker-rhel-systemd/actions/workflows/build.yml) 

Docker containers with systemd.

## Tags

### Ubuntu

  - `22.04`, `jammy`, `latest`
  - `20.04`, `focal`

### Rocky Linux

  - `9`, `latest`
  - `8`

## How to Use

  * `docker run --detach --privileged --volume=/sys/fs/cgroup:/sys/fs/cgroup:rw --cgroupns=host melihsavdert/docker-rockylinux-systemd:latest`

## Author

Created in 2024 by Melih Savdert

## License

GNU GENERAL PUBLIC LICENSE (see [LICENSE](LICENSE) file)