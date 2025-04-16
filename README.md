## Entry point

1. clone repo
2. create a file .env
3. execute command `git submodule update --init --recursive` to rebuild submodules folders. Only if is first time
4. execute command `docker compose up --build`

## Docker

docker build -f dockerfile.prod -t nombre-aqui .

docker compose -f docker-compose.prod.yml build
