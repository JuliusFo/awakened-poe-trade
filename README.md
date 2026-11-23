> [!NOTE]
> **Unofficial build with Inscribed Ultimatum price checking (3.30 Covens).** This fork is the official
> app plus price checking for Inscribed Ultimatums, until the official app supports them. Use the
> official release again once it does: this build shows the official update notice but does not install
> updates by itself.
>
> Changes on branch `viscera-local`, on top of upstream `db34867`:
> - Inscribed Ultimatum parsing and trade filters (challenge, reward, sacrifice, reward unique, area
>   level, reward tier via the monster life/damage lines), ported from
>   [vandlol's branch](https://github.com/SnosMe/awakened-poe-trade/issues/1921).
> - Added the missing *Blood-filled Vessel* fragment to the English item data.
> - Viscera use the official implementation (this fork's earlier interim Viscera support was dropped),
>   with the modifier enabled by default so the first search is not the whole body-part category.
>
> Report problems with this build here, not on the upstream issue tracker. All credit for the app goes to
> [SnosMe](https://github.com/SnosMe/awakened-poe-trade); licensed under MIT like the original.

# ![Awakener's Orb](https://web.poecdn.com/image/Art/2DItems/Currency/TransferOrb.png) Awakened PoE Trade

[![](https://user-images.githubusercontent.com/4292308/153364874-dde23599-278c-4350-8d86-dadbc4b978b3.svg)](https://somsubhra.github.io/github-release-stats/?username=SnosMe&repository=awakened-poe-trade)
[![](https://user-images.githubusercontent.com/4292308/153364769-e4fe1e82-1bbc-46ac-8a3c-f5a98a5667cc.svg)](https://patreon.com/awakened_poe_trade)
[![](https://user-images.githubusercontent.com/4292308/153364565-7a545d26-e617-4a33-a919-ff90d8feda3d.svg)](https://github.com/SnosMe/awakened-poe-trade/issues/22)


➡ [Download for Windows & Linux](https://snosme.github.io/awakened-poe-trade/download) ⬅

## Tool showcase

| Gem | Rare | Unique | Currency |
|-----|------|--------|----------|
| ![](https://i.imgur.com/LTsH2DZ.png) | ![](https://i.imgur.com/2XL5Wl8.png) | ![](https://i.imgur.com/UTV6prE.png) | ![](https://i.imgur.com/dQ9Sns6.png) |

### Development

See [DEVELOPING.md](./DEVELOPING.md)

### Acknowledgments

- [libuiohook](https://github.com/kwhat/libuiohook)
- [RePoE](https://github.com/brather1ng/RePoE)
- [poeprices.info](https://www.poeprices.info/)
- [poe.ninja](https://poe.ninja/)

![](https://i.imgur.com/MATqhv7.png)
