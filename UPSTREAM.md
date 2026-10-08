# Upstream

| | |
| --- | --- |
| Project | OWASP Juice Shop |
| Repository | https://github.com/juice-shop/juice-shop |
| Version | v20.2.0 |
| Commit | 5658473cf8814459bf89000ce373b20ed0b4eb37 |
| Licence | MIT |

`build/shop/app/` is that commit, unchanged, without its Git history. `build/shop/Dockerfile` is
upstream's Dockerfile with one change: npm resolves dependencies as of the release date
(`npm_config_before`), because Juice Shop ships no lockfile. To update, replace `build/shop/app/`
with a newer release, then change this table and that date.
