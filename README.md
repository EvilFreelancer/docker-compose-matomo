# Docker composition of Matomo

Basic repo with composition of docker containers required for Matomo (formerly Piwik)

## How to use

Clone the repo, then copy config from example:

    cp docker-compose.yml.dist docker-compose.yml

Start composition of containers:

    docker-compose up -d

Go to http://localhost in your browser.
