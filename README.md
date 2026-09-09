# clients.fresthomes.com

Frest Homes client area (after first meeting). AES-GCM encrypted pages, registered e-mail + passcode (PBKDF2-SHA256 300k, per-person wrapped keys). Per-client project pages under p/<slug>/ use their own content key wrapped only for that client and the Frest team. Add/revoke: `clients/data/users.json` + `projects.json`, rebuild, upload. Generator in Drive `WEB/gates/`.
