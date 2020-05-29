### Demonstrating error with yarn workspaces

Prerequisites:
- docker
- docker-compose

install dependencies:
`docker-compose run --rm yarn install --ignore-optional --ignore-scripts`

attempt to run build:
`docker-compose run --rm yarn workspace plugin-poc build`
