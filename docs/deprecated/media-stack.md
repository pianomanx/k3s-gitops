# media-stack

> *Note*: this document is a work in progress

## Cluster addresses

- nzbget.default.svc.cluster.local
- jackett.default.svc.cluster.local
- nzbhydra2.default.svc.cluster.local
- qbittorrent-gui.default.svc.cluster.local
- sonarr.default.svc.cluster.local
- radarr.default.svc.cluster.local
- plex-tcp.default.svc.cluster.local
- xteve.default.svc.cluster.local:34400
- xteve.default.svc.cluster.local:34400/xmltv/xteve.xml

## Debugging connectivity

```bash
apt install -y dnsutils iputils-ping
nslookup nzbget.default.svc.cluster.local
ping nzbget.default.svc.cluster.local
```
