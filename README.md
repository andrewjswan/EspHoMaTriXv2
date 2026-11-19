# EspHoMaTriX version 2 (EHMTXv2)

![GitHub contributors](https://img.shields.io/github/contributors/lubeda/EspHoMaTriXv2)
![GitHub last commit](https://img.shields.io/github/last-commit/lubeda/EspHoMaTriXv2)
![GitHub commit activity](https://img.shields.io/github/commit-activity/t/lubeda/EspHoMaTriXv2)

> [!WARNING]
> **Project Migrated & Renamed:** As noted in the announcement below, the original author (@lubeda) has officially ended development of **[EspHoMaTriXv2](https://github.com/lubeda/EspHoMaTriXv2)**. 
>
> To continue maintaining and evolving this component for future ESPHome versions, the project has migrated to a standalone repository at [**andrewjswan/pixel-clock**](https://github.com/andrewjswan/pixel-clock) and has been renamed to **`pixel-clock`**.
>
> This repository is now archived and will no longer receive updates. All future features, bug fixes, and documentation are available exclusively in the new repository — please update your ESPHome `external_components` configuration accordingly.

> [!IMPORTANT]
> **End of development:** Version **`2026.9.1`** is the last release of **EspHoMaTriXv2**. There will be no further updates, features or bug fixes.
>
> A big **thank you** to all users of EHMTX! Your feedback, bug reports, pull requests, icons, ideas and support over the years made this project what it is. 🙏
>
> If you are looking for an actively maintained firmware for your pixel clock (e.g. Ulanzi TC001), have a look at [**AWTRIX NG**](https://github.com/Blueforcer/awtrix-ng) ([documentation](https://blueforcer.github.io/awtrix-ng)), the successor of AWTRIX 3.
>
> See the [Migration Guide](./migration.md) for help moving from EHMTX to AWTRIX NG.

## Introduction

**EspHoMaTriXv2** is a flexible, highly customizable DIY LED Matrix display, built with a 8×32 RGB LED panel and implemented with [esphome.io](https://esphome.io)

![sample animation](./images/sample1.gif)

You can control it with Home Assistant using service calls or by using lambda with ESPHome.

## Disclaimer

THE SOFTWARE IS PROVIDED “AS IS”, use at your own risk!

## Special Thanks

- **[andrewjswan](https://github.com/andrewjswan)** Boot animation centered. `alert_screen` and [issue](https://github.com/lubeda/EspHoMaTriXv2/issues?q=is%3Aissue+author%3Aandrewjswan) and the [additions](https://github.com/lubeda/EspHoMaTriXv2/pulls?q=is%3Apr+author%3Aandrewjswan) to 2023.9.1
- **[trip5](https://github.com/trip5/Matrix-Fonts)** for his work on optimized fonts and user support and work on the wiki

## Thanks
- **[blakadder](https://github.com/blakadder)** for his contribution (cleanup README.md, fixed sample)
- **[dbuezas](https://github.com/dbuezas)** for his fonts [infos](https://github.com/lubeda/EspHoMaTriXv2/issues/63)
- **[jfurtner](https://github.com/jfurtner)** for his the on_start_running trigger and a new parameter
- **[andrew-codechimp](https://github.com/andrew-codechimp)** for his contribution (display on/off & del_screen "*" & show_clock with 0) and improved blueprint selection
- **[jd1](https://github.com/jd1)** for his contributions
- **[aptonline](https://github.com/aptonline)** for his work on the Ulanzi hardware
- **[wsbtak](https://github.com/wsbtak)** for the work on the Ulanzi hardware
- **[ofirsnb](https://github.com/ofirsnb)** for his contributions
- **[pplucky](https://user-images.githubusercontent.com/16407309/224850723-634c9b2d-55d9-44f2-9f93-765c0485b090.GIF)** for his 8x32 GIF animation
- **[dennisse](https://github.com/dennisse)** Auto brightness for the Ulanzi
- **[hco](https://github.com/hco)** fixing documentation
- **[geekofweek](https://github.com/geekofweek)** fixed sample YAML, cleanup documentation
- **[joncar](https://github.com/joncar)** fixed scroll small text
- **[TheGroundZero](https://github.com/TheGroundZero)** PRs and discussion about bootloop
- **[N3rdix](https://github.com/N3rdix)** PRs
- **[lukasleitsch](https://github.com/lukasleitsch)** PRs
- **[trvrnrth](https://github.com/trvrnrth)** PRs with fixing an error
- **[malinovsku](https://github.com/malinovsku)** Issues and testing.
- **[chertvl](https://github.com/chertvl)** Issues and testing.
- **[fthiery](https://github.com/fthiery)** for improving documentation
- **[pznamenskii](https://github.com/pznamenskii)** for improving documentation
- **[mik-at](https://github.com/mik-at)** fixing typos
- **[DT-art1](https://github.com/DT-art1)** preparing for ESPHome 2025.5.0
- **[genehand](https://github.com/genehand)** for the speed optimization
- **[skgsergio](https://github.com/skgsergio)** preparing 2025.12.0
- **[Nathanator](https://github.com/Nathanator)** for improving the wiki
- **Everybody** who has fun by using this software
- **Everybody** who found bugs/issues and reported them!
