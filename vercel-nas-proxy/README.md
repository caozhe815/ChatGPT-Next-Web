# Vercel NAS Proxy

This folder is a minimal Vercel reverse proxy for Calibre-Web/OPDS and DSM.

Public URLs:

- `https://book.caozhe.net` -> Calibre-Web / OPDS
- `https://nas.caozhe.net` -> Synology DSM login

Origin URLs:

- `https://book-origin6.caozhe.net`
- `https://nas-origin6.caozhe.net`

Do not change existing `caozhe.net` apex, wildcard, or VPN/hy2 records.

The origin hostnames should be AAAA-only and updated to the current NAS IPv6 address by the NAS scheduled script.
