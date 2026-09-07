# `pascaliske/docker-package`

> TBD

[![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/pascaliske/package/latest?style=flat-square)](https://hub.docker.com/r/pascaliske/package) [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/pascaliske/package/latest?style=flat-square)](https://hub.docker.com/r/pascaliske/package) [![Docker Pulls](https://img.shields.io/docker/pulls/pascaliske/package?style=flat-square)](https://hub.docker.com/r/pascaliske/package) [![GitHub Tag](https://img.shields.io/github/v/tag/pascaliske/docker-package?style=flat-square)](https://github.com/pascaliske/docker-package) [![Build Status](https://img.shields.io/github/actions/workflow/status/pascaliske/docker-package/image.yml?branch=main&label=build&style=flat-square)](https://github.com/pascaliske/docker-package/actions) [![GitHub Last Commit](https://img.shields.io/github/last-commit/pascaliske/docker-package?style=flat-square)](https://github.com/pascaliske/docker-package) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://opensource.org/licenses/MIT) [![Awesome Badges](https://img.shields.io/badge/badges-awesome-green.svg?style=flat-square)](https://github.com/Naereen/badges)

## Image

| Registry                  | Image                                                                                               |
| ------------------------- | --------------------------------------------------------------------------------------------------- |
| GitHub Container Registry | [`ghcr.io/pascaliske/package`](https://github.com/pascaliske/docker-package/pkgs/container/package) |
| Docker Hub                | [`pascaliske/package`](https://hub.docker.com/r/pascaliske/package)                                 |

The following platforms are available for this image:

```bash
$ docker run --rm mplatform/mquery ghcr.io/pascaliske/package:latest
Image: ghcr.io/pascaliske/package:latest
 * Manifest List: Yes
 * Supported platforms:
   - linux/amd64
   - linux/arm/v7
   - linux/arm64
```

## Usage

To use this image pull it from one of the following registries:

```bash
# github container registry
docker pull ghcr.io/pascaliske/package

# docker hub
docker pull pascaliske/package
```

## Verification

The OCI images are **keylessly** signed using [`cosign`](https://docs.sigstore.dev/cosign/verifying/verify/) and can be can be verified:

```shell
cosign verify ghcr.io/pascaliske/package:main \
  --certificate-identity-regexp "^https://github.com/pascaliske/docker-package.*$" \
  --certificate-oidc-issuer https://token.actions.githubusercontent.com
```

> [!NOTE]
> Verification succeeds only if the artifact was signed by the GitHub Actions workflow in this repository.
> Any modification of the artifact or signing from a different identity will cause verification to fail.

## License

[MIT](LICENSE.md) – © 2026 [Pascal Iske](https://pascaliske.dev)
