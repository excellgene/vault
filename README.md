# excellvault

## Usage

### Configuration

1. Create self-signed SSL certificate
  1. `cd .docker/pki/`
  2. cp req.conf.exemple req.conf
  3. open `req.conf` and replace all the "X"
  4. `openssl req -x509 -nodes -days 3650 -newkey rsa:2048 -keyout cert.key -out cert.cer -config req.conf -extensions v3_req`
1. `.env` file
  1. `cp .env.exemple .enmv`
  2. open `.env` and fill it

### Run

    docker-compose up -d

### Clients

[Bitwarden](https://bitwarden.com/download/)
