# docker-tftpd-hpa

## Usage:

Start the tftp server:

`docker run -d --name=tftpd -v /srv/docker/tftpboot:/var/lib/tftpboot:ro sheeprine/tftpd-hpa:latest`
