# PR assets

Hosting branch for icons and gallery screenshots referenced from open PRs against
[getumbrel/umbrel-apps](https://github.com/getumbrel/umbrel-apps).

Source of the icon: [namecoin/namecoin-graphics](https://github.com/namecoin/namecoin-graphics)
(`svg/namecoin-coin.svg`, `png/namecoin-coin_*.png`).

| App | PR | Folder |
| --- | --- | --- |
| Namecoin Core | [#4962](https://github.com/getumbrel/umbrel-apps/pull/4962) | [`assets/namecoin/`](assets/namecoin) |
| Namecoin ElectrumX | [#4963](https://github.com/getumbrel/umbrel-apps/pull/4963) | [`assets/namecoin-electrumx/`](assets/namecoin-electrumx) |

The screenshots are rendered from the apps' built-in dashboards
(`namecoin/web/public/index.html` and `namecoin-electrumx/web/public/index.html`),
which ship with the corresponding container images on `ghcr.io/mstrofnone/`.
