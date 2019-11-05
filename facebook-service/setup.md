---
description: How to set up the combinary facebook service on your own server
---

# Setup

#### SSH

```text
git@git.acolono.net:combinary/collector-facebook.git
```

#### HTTPS

```text
https://gitlab.acolono.net/combinary/collector-facebook.git
```

1. Before starting the service add the required environment variables in the facebook.env for dev, live environment and the app id and other required variables.
2. Set the development variable to true or false for a live environment.
3. Move to the docker folder and start the service

```text
cd collector-facebook/docker
docker-compose up -d
```

The application is then running on your server.

