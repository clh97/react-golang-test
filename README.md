# A1-Front and A2-Back

Cloning: `git clone --recursive https://github.com/clh97/smart-mei.git`

* (WIP) A1-Front
* A2-Back is a golang/graphql application that serves as intermediary service to `viacep.com.br`

# Docker-compose

`docker-compose up --build` in root directory should run up both A1 and A2 applications

# A2-Back
* Example query for /graphql endpoint can be found on a2-back/README.md
* A2-Back runs with Compile-Daemon for golang, so its expected to recompile after each files