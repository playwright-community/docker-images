## Docker Images for Playwright for Chrome Channels

This repository contains Python 3.8 Docker Images for [Playwright](https://github.com/microsoft/playwright) for Chrome Channels for Ubuntu 20.04 LTS.

### Channels:
- Chrome-Stable 
- Chrome-Beta
- Chrome-Dev

### Docker Images

- The images are hosted on ghrc.io. 
- The images are tagged as version which is the playwright version on PyPI. 
- The latest images are tagged as `latest`

#### Chrome Stable 


```sh
# Latest
docker pull ghcr.io/playwright-community/docker-images/playwright-chrome-stable:latest
# Version
docker pull ghcr.io/playwright-community/docker-images/playwright-chrome-stable:1.11.1
```

#### Chrome Beta


```sh
# Latest
docker pull ghcr.io/playwright-community/docker-images/playwright-chrome-beta:latest
# Version
docker pull ghcr.io/playwright-community/docker-images/playwright-chrome-beta:1.11.1
```
#### Chrome Dev


```sh
# Latest
docker pull ghcr.io/playwright-community/docker-images/playwright-chrome-dev:latest
# Version
docker pull ghcr.io/playwright-community/docker-images/playwright-chrome-dev:1.11.1
```

# LICENSE
The project is licensed under APACHE 2.0 LICENSE