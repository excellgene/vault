# POC Vaultwarden

## Intersting documentation

### enabling HTTPS (big deal)

link to doc here : [Encrypt](https://github.com/dani-garcia/vaultwarden/wiki/Running-a-private-vaultwarden-instance-with-Let%27s-Encrypt-certs)

Implies :

- DynDNS (DuckDNS or Caddy as RProxy)
- Let's Encrypt

## Usage

### Configuration

1. provide a SSL private and certificate file inside `.docker/pki/`
1. create `.env` file based on `.env.exemple` and fill it with the name of the private key and certificate provided before

### Run

    docker-compose up -d

### Clients

[Bitwarden](https://bitwarden.com/download/)
