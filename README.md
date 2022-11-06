# Deploy Node.js application with Caddy, Docker & docker-compose on DigitalOcean

![]()
<img src="./docker.png" style="max-width: 500px;width=100%" />

## Why Caddy?
* Automatic TLS (SSL/ HTTPS)
* Easy configuration

1.0 Configure Docker & Caddy Server

    1.1 Create Dockerfile
    1.2 Create docker-compose.yml file
    1.3 Create Caddyfile
    1.4 Create deploy script

2.0 Create Digital Ocean Droplet

3.0 Point domain at droplet

4.0 Deploy application

    4.1 SSH in to server
    4.2 Git pull repo `git clone https://github.com/TomDoesTech/caddy-nodejs-docker-tutorial.git`
    4.3 Run deployment script

5. Test SSL certificate
`https://www.ssllabs.com/ssltest/`
