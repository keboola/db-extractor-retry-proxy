# db-extractor-retry-proxy
Simple PHP class for retry request

## Usage
Require with composer:

```yml

    composer require keboola/db-extractor-logger

```

## Development

Developed with TTD. Requires Git, Composer, Docker and Docker Compose.

Clone repository, install dependencies and run tests:
```
    git clone git@github.com:keboola/db-extractor-retry-proxy.git
    cd db-extractor-retry-proxy
    docker-compose build
    docker-compose run app composer install
    docker-compose run app
```
