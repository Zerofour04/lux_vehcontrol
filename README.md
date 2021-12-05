# 🚨lux_vehcontrol-WMServerSirens

## 🚨ELS-Version:
[ELS-FiveM-WMServerSirens](https://github.com/Zerofour04/ELS-FiveM-WMServerSirens)

## ⭐Credits
[Lt.Caine](https://forum.cfx.re/t/release-luxart-vehicle-control/17304)
- I uploaded the resource because the resource is not available on GitHub
- Integrated [WMServerSirens](https://github.com/Zerofour04/WMServerSirens)

## 🧱Requirements
- [WMServerSirens](https://github.com/Zerofour04/WMServerSirens)
- [fxserver](https://docs.fivem.net/docs/server-manual/setting-up-a-server/)

## ℹ️Information
This server resource allows for synchronized ELS-style siren control and features, as well as synchronized indicator and hazard lights. It has been in use on the High-Speed Gaming server for several months and has proven effective.

I was planning on releasing this resource at a later date, after polishing it up and addressing a few issues. However, it has been brought to my attention that stolen versions of the code have been sold for (sometimes) large sums of money. This is not only very unfortunate (especially for those who paid money for this free resource), but also unacceptable. I’ve thus decided to bring it to the public: to prevent others from falling victim to the predators out there, and also since it was slated for release anyway.

The code is not the best, by any means. It was made while I was learning the basics of Lua and scripting for FiveM (in fact, I’m still learning). But, what’s important is that it works and people enjoy using it.

## 📦Features:
- Does not affect or control vehicle emergency lighting (this is not ELS).
- All features are synchronized for all players.
- Intuitive controller support (uses similar layout as ELS).
- Full siren and horn tone control (mute, manual tones, air horn, main siren tones, and auxiliary siren tone).
- Main siren will remain on when exiting the vehicle (this is intentional and meant to be realistic).
- Hazard and indicator light control.
- Indicators turn off automatically after a short delay (if the vehicle is moving).

## 🛠️Installation:
1. Place the lux_vehcontrol folder inside your server's resources folder
2. Add `start lux_vehcontrol` to your server's server.cfg file