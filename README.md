# Wireguard peer-to-site
### Wireguard configuration for sharing 3rd party vpn

Repo contains 2 wireguard.conf files. The first one (vpn.conf) responsible for a connection to a 3rd party vpn, while the wg0.conf configuring a local subnet for routing traffic from endpoins to a vpn service.

Points to improve:

- Improve readability and add comments
- Wrap everything into docker containers to isolate a server
- ...
