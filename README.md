# Pihole + DNS over TLS

WARNING: This might actually be a bad idea: https://www.reddit.com/r/pihole/comments/unmkx7/safe_to_run_pihole_as_a_dnsoverhttps_server/

# Deploy

1. Point your domain to your server
2. Replace `dns01.example.com` with your domain both in `docker-compose.yml` and `Caddyfile`
3. Update pihole's password (and maybe your timezone) in `docker-compose.yml`
4. Run `docker-compose up -d`

# Use from your Android phone

1. Open Settings
2. Navigate to Network & Internet
3. Tap on Advanced
4. Select Private DNS
5. Write your domain