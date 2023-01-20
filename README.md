# Pihole-Unbound

A docker configuration based on the project at https://github.com/chriscrowe/docker-pihole-unbound using the one-container setup.

TreafikV2 labels are integrated into the compose file for reverse proxy + SSL support. For use with my matching runestone-traefik config or your own instance.

## Roadmap:
- Create deployment script to automatically configure docker host for unbound support
- Integrate gravitysync or similar tool for backing up config, syncing to multiple other pihole-unbound instances. 
- Create tutorial to demonstrate deployment and traefikV2 usage
- Further test traefikV2 handling