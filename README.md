# Docker images with systemd

[![Build](https://github.com/msavdert/docker-rhel-systemd/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/msavdert/docker-rhel-systemd/actions/workflows/build.yml) 

This docker images can build containers capable to use systemd.

## Tags

### Rocky Linux - melihsavdert/docker-rockylinux-systemd

  - `9`, `latest`
  - `8`

### Oracle Linux - melihsavdert/docker-oraclelinux-systemd

  - `9`, `latest`
  - `8`
  - `7`

### Ubuntu - melihsavdert/docker-ubuntu-systemd

  - `22.04`, `jammy`, `latest`
  - `20.04`, `focal`

## How to Use

```
docker run \
  --privileged \
  --detach \
  --volume=/sys/fs/cgroup:/sys/fs/cgroup:rw \
  --cgroupns=host \
  melihsavdert/docker-oraclelinux-systemd:latest
```

## Author

Created in 2024 by Melih Savdert

## License

GNU GENERAL PUBLIC LICENSE (see [LICENSE](LICENSE) file)
