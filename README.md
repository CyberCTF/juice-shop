# OWASP Juice Shop

[OWASP Juice Shop](https://owasp-juice.shop) by Bjoern Kimminich and the OWASP Juice Shop
contributors: an insecure online shop with more than 100 hacking challenges. This repository runs
it with [Isoloom](https://www.isoloom.com): [`isoloom.yml`](isoloom.yml) describes the machine,
and the upstream source in [`build/shop/app/`](build/shop/app) builds with its own Dockerfile, pinned to its release date.

| Machine | Service |
| --- | --- |
| shop | Juice Shop on port 3000 |

## Run it

```bash
isoloom generate
isoloom run docker
```

Then open http://localhost:3000/. The same spec runs as Docker on a local VM (`docker-vm`), on a
cloud VM (`cloud-docker`) or on Kubernetes. Lab guide:
[Pwning OWASP Juice Shop](https://help.owasp-juice.shop).

Upstream version and commit: [UPSTREAM.md](UPSTREAM.md).

## Licence

MIT, as Juice Shop ([LICENSE](LICENSE)). This application is deliberately vulnerable: keep it
isolated.
