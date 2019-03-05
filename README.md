# Gluu Server Docker Edition (DE)

## Overview
DE includes Linux container assets for Gluu Server Community Edition (CE). DE is compatible with Docker, Kubernetes, and other container environments.

## Docs

Visit the official [Gluu Server DE documentation](https://gluu.org/docs/de/3.1.4). 

## Code Repositories

Repositories for supported images are shown below:

- [config-init](http://github.com/GluuFederation/docker-config-init)
- [opendj](http://github.com/GluuFederation/docker-opendj)
- [oxauth](http://github.com/GluuFederation/docker-oxauth)
- [oxtrust](http://github.com/GluuFederation/docker-oxtrust)
- [nginx](http://github.com/GluuFederation/docker-nginx)
- [key-rotation](https://github.com/GluuFederation/docker-key-rotation)
- [oxshibboleth](https://github.com/GluuFederation/docker-oxshibboleth)
- [oxpassport](https://github.com/GluuFederation/docker-oxPassport)

## Image Repositories

Images are hosted at Docker Hub:

`<image>:latest` are the latest builds currently.

- [config-init](https://hub.docker.com/r/gluufederation/config-init)
- [openldap](https://hub.docker.com/r/gluufederation/openldap)
- [opendj](https://hub.docker.com/r/gluufederation/opendj)
- [oxauth](https://hub.docker.com/r/gluufederation/oxauth)
- [oxtrust](https://hub.docker.com/r/gluufederation/oxtrust)
- [nginx](https://hub.docker.com/r/gluufederation/nginx)
- [key-rotation](https://hub.docker.com/r/gluufederation/key-rotation)
- [oxshibboleth](https://hub.docker.com/r/gluufederation/oxshibboleth)
- [oxpassport](https://hub.docker.com/r/gluufederation/oxpassport)

## Examples

[Single Host](./examples/single-host/)

- The directory contains `README.md` as a guide to deploy a basic single-host Gluu server stack.

[Swarm](./examples/multi-hosts/)

- The directory contains `README.md` as a guide to deploy a basic multi-hosts Gluu server stack.

[Google Kubernetes Engine](./examples/kubernetes/gke)

- The directory contains `README.md` as a guide to deploy a basic Gluu server stack on Google Kubernetes Engine.

[Minikube](./examples/kubernetes/minikube)

- The directory contains `README.md` as a guide to deploy a basic Gluu server stack on Minikube.

## License

Gluu Server DE is available under the [GLUU SUPPORT license](./LICENSE).
