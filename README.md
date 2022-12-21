# ThreatClassic2 for 1.14.x Hermes Proxy
Modified version of ThreatClassic2 for displaying reasonably accurate estimates of a monster's threat table on the 1.14.x client with Hermes Proxy.


## Install
 - Press the green code button and click download zip
 - Rename ThreatClassic2-master to ThreatClassic2 and drag it into your addon folder

## FAQ

**Q: Why am I not seeing other players in ThreatClassic2?**
 
A: Other players must have ThreatClassic2 or a compatible AddOn enabled in order to track their threat similar to how KLH Threat Meter/Omen required compatible AddOns communicating threat to one another in Vanilla/TBC.

**Q: Why isn't ThreatClassic2 using the built-in threat API?**

A: To answer simply, it can't! In vanilla server did not send threat to client, which means we must rely on combat log parsing.

**Q: How does ThreatClassic2 handle multiple targets?**

A: The combat log in WoW Classic is fortunately much more detailed than that which was available in the game originally before patch 2.4. This allows us to track NPCs by GUID (global unique identifier), and there should be no issues with mobs having the same name and threat becoming muddled between them. It is also designed in such a way that effects that are meant to add divided threat between active targets, such as heals and buffs, are able to do so.

## Sreenshots
<img src="https://i.imgur.com/7ipFacm.png">

## License

[MIT](license/ThreatClassic2)

Copyright (c) 2019 Dennis-Florian Herr
