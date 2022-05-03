# pi-hole-k8

Ad block + Local DNS server

```bash
# cron entry for restart issue

@reboot mkdir /run/systemd/resolve && touch /run/systemd/resolve/resolv.conf

```