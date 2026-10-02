# unRAID templates — MozAIk Labs

Community Applications templates for software by [MozAIk Labs](https://mozaiklabs.fr).

| App | Template | Image |
|-----|----------|-------|
| **Tune** — self-hosted multi-room music server | [`templates/tune.xml`](templates/tune.xml) | [`renesenses/tune`](https://hub.docker.com/r/renesenses/tune) (amd64, arm64) |

## Tune

Tune indexes your local library (FLAC, DSD…), brings in Qobuz, Tidal and Deezer, and plays bit-perfect to DLNA/UPnP renderers, Chromecast, AirPlay and Squeezebox players from a web interface on port 8888.

- **Network**: host (required for DLNA, mDNS and AirPlay discovery).
- **Paths**: `/music` (your library, read-only) and `/data` (database, settings, artwork cache).
- **Support**: https://mozaiklabs.fr/forum

To add this repository manually before it appears in Community Applications, use *Docker › Add Container › Template repositories* and paste `https://github.com/renesenses/unraid-templates`.
