# Rustic 301 via Dockerized Nginx

Sets up a 301 redirect.

> We use this to provide a permalink to our Discord server.
> 
> https://discord.mieuxvoter.fr → https://discord.gg/k9YRuZPSZs


## How to use

1. Copy the `.env.dist` file to `.env`:

    cp .env.dist .env

2. Then, configure `.env`.
3. Run docker compose:

    docker compose up
