# Rustic 301 via Dockerized Nginx

[![MIT](https://img.shields.io/github/license/MieuxVoter/discord.mieuxvoter.fr?style=for-the-badge)](./LICENSE)
[![Join the Discord chat at https://discord.mieuxvoter.fr](https://img.shields.io/discord/705322981102190593.svg?style=for-the-badge)](https://discord.mieuxvoter.fr)

Sets up a single 301 redirect.

> We use this to provide a permalink to our Discord server.
> 
> https://discord.mieuxvoter.fr → https://discord.gg/k9YRuZPSZs


## How to use

1. Copy the `.env.dist` file to `.env`:
   ```shell
   cp .env.dist .env
   ```
2. Then, configure `.env`.
3. Run docker compose:
   ```shell
   docker compose up
   ```

