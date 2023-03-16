# docker-desktop-cache-dropper
Workaround for [Docker Desktop's VM not dropping cache](https://github.com/docker/for-win/issues/13227) causing excessive memory consumption

This workaround is based on the fix described in https://github.com/microsoft/WSL/issues/8725#issuecomment-1406646712

## How to apply the workaround
Run ``docker compose up -d``

* The container is restarted automatically when your PC reboots
