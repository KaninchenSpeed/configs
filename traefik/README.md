# Traefik

Traefik uses two types of configuration

## Static Configuration

### Traefik Config
> This config configures entrypoints and cert providers (for tls/https)

Stored in: `/traefik.yml`

## Dynamic Configuration
> This config describes services and routers and can be done in multiple ways.

### Files
Stored in: `/dynamic`

#### example_https.yml
A simple example exposing a http service via https using traefik to encrypt the traefik and get the certs.