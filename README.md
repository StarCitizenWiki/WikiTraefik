# Star Citizen Wiki Traefik

This is the traefik configuration powering the Star Citizen Wiki.

## Configuration
To use the cloudflare dns challenge you need to set `CF_API_EMAIL` and `CF_DNS_API_TOKEN` in `docker-compose.yaml`.  
You can create an DNS API Token [here](https://dash.cloudflare.com/profile/api-tokens).

The token needs the following permissions:
  * Zone: Read
  * DNS: Edit

Don't forget to add `basicauth` credentials to `docker-compose.yaml`.  
