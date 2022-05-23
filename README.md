# centos-6-vault-image

[![Docker Pulls](https://img.shields.io/docker/pulls/scorpio2002/centos-8-vault-image)](https://hub.docker.com/r/scorpio2002/centos-8-vault-image/tags?page=1&ordering=last_updated)

Because of CentOS 6 End of life mirrorlist is not accessible from centos image, I've created new image based on `centos:8`
with changed baseurl to http://vault.centos.org, to fix this issue.

Thank for such fix information received from [Error: Failed to download metadata for repo ‘appstream’: Cannot prepare internal mirrorlist: No URLs in mirrorlist — Centos 8 Fix](https://yegorshytikov.medium.com/error-failed-to-download-metadata-for-repo-appstream-cannot-prepare-internal-mirrorlist-no-959768e5f8e5)

DockerHub Image should be available here: `scorpio2002/centos-8-vault-image:8`

So you can change your image from `centos:8` to this one and use it.
