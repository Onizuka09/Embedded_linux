# gooeygui-layer 
a gooeyGUI Layer
## Usage 
- clone the repo
- install dependencies git curl tar and vcstool for vsctool you can use the scripts/setup_vcstool.sh
- source the scripts/setup-helper.sh
- run the scripts/setup-project.sh
- first install docker and docker compose LINK
- in a seperate terminal run docker compose watch to sync any changes made on the Dockerfile or docker-compose.yml
- in an other terminal run cd docker && docker compose run -- rm yocto-builder
