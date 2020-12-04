# WordpressDockerInstall

This repository is a personnal ready-to-use repository for WordPress using [WSL2](https://docs.microsoft.com/fr-fr/windows/wsl/install-win10) and [Docker](https://www.docker.com/products/docker-desktop) interface.

## Bashrc
In order to simplify the use of docker, please enter the following line in your bashrc (sudo nano ~/.bashrc):
* alias dc='docker-compose --env-file .env $*'

*Note: Those alias are totally optionals, because they override your local commands*

## Docker
To start Docker, please make:

* cd &lt;project dir&gt;/docker
* docker-compose up -d  (or *dc up -d* if you use aliases)

To stop Docker, please make:
* docker-compose down (or *dc down* if you use aliases)

## Contributing

Pull request are welcome.
