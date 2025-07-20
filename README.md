<!--[![GPLv3][badge-license]](https://www.gnu.org/licenses/gpl-3.0) -->
[badge-license]: https://img.shields.io/badge/License-GPLv3-lightgray
<!--![Supports Royalty][badge-dlc-royalty] supports Royalty DLC-->
[badge-dlc-royalty]: https://img.shields.io/badge/DLC-Royalty-gold
<!--![Supports Ideology][badge-dlc-ideology] supports Ideology DLC-->
[badge-dlc-ideology]: https://img.shields.io/badge/DLC-Ideology-indianred
<!--![Supports Biotech][badge-dlc-biotech] supports Biotech DLC-->
[badge-dlc-biotech]: https://img.shields.io/badge/DLC-Biotech-mediumturquoise
<!--![Supports Anomaly][badge-dlc-anomaly] supports Anomaly DLC-->
[badge-dlc-anomaly]: https://img.shields.io/badge/DLC-Anomaly-darkseagreen
<!--![Supports Odyssey][badge-dlc-odyssey] supports Odyssey DLC-->
[badge-dlc-odyssey]: https://img.shields.io/badge/DLC-Odyssey-mediumpurple

# [RCP] Rebalance
![](About/Preview.png)\
[![GPLv3][badge-license]](https://www.gnu.org/licenses/gpl-3.0) ![Supports Royalty][badge-dlc-royalty]

> [!IMPORTANT]
> Requires [RimWorld Royalty](https://store.steampowered.com/app/1149640/RimWorld__Royalty/).\
> Use [XML Extensions](https://steamcommunity.com/sharedfiles/filedetails/?id=2574315206) for settings (optional).

## Deserter Overhaul
- Better Deserter (enabled by default)
- - Prevents spawning with undesireable traits.
- - Must be capable of caring, skilled labor, and social.
- - Shooting skill between 6 and 12.
- - Always baseliner, no more hussars.
- Deserter Always Female (disabled by default)

## Permits
### Awarded permit points
The vanilla permit point progression is Acolyte + 1 -> Knight + 1 -> Praetor + 1 -> Baron + 1 -> Archon +1 -> 5 total permit points.

I like the idea of restricting colonists to one or two trees, but the new additions call for more points. Baron now awards 2 points for a total of 5 for Barons and 3 points for Archons for a total of 8. This should retain a tighter permit tree in the early game while awarding more freedom in the late game.

### Combat drop
|  | Charge rifle drop | Prestige armor drop |
|---:|:---:|:---:|
| Value | 1010 | 2690 ($1975+715$) |
| Cooldown | 60 | 150 |
| Daily value | 16.8 | 17.9 |
| Favor | 10 | 22 |

Both of these drops require an Archon. The prestige armor drop is a prestige recon armor set with a helmet. Since it's a late-game permit, and the player has presumably already met the armor requirements for their royal pawn, this is balanced to make honor quest rewards more attractive for colonies with Archons. It's not dramatically more valuable than other permits when you consider daily value with cooldowns or the honor to market value ratio.

For example, the vanilla food drop permit has an honor:market value ratio of 120 ($480/4$). The charge rifle drop is 101. The prestige armor drop is 122.

With Combat Extended, the charge rifle drop comes with 300 6x24mm rounds (market value 150). This increases the daily value to 19.3 and the honor:market value ratio to 116.

### Food drop
|  | Food drop | Fine meal drop | Lavish meal drop |
|---:|:---:|:---:|:---:|
| Type | Packaged survival meal | Fine meal | Lavish meal |
| Value | 480 ($20*24$) | 400 ($20*20$) | 800 ($20*40$) |
| Cooldown | 45 | 45 | 60 |
| Title | Acolyte | Acolyte | Baron |
| Favor | 4 | 4 | 6 |
| Daily value | 10.6 | 8.88 | 13.3 |

The new food drops are meant to satisfy title requirements, whereas the vanilla food drop is a general food solution for the colony. Fine meals are required for Acolyte+ colonists, and lavish meals are required for Baron+. Since this is meant to prevent mood debuffs for a short period of time when the colony isn't able to produce high quality meals, I didn't balance for market value.

### Glitterworld med drop
This only provides 5 medicine, worth 250 market value. It's great for single-pawn emergencies, but anyone with colonies of 12+ (reasonable considering the Baron title requirement) will find it lacking for something like a malaria outbreak. I've upped it to 10 and increased the cooldown to 60 days.

It's a negligible net daily value increase (5.55 -> 8.33) that brings it closer to the rest of the vanilla permits. This also makes it possible to cure paralytic abasia and blood rot for one pawn with a single drop, and makes bioregeneration cycles more viable for colonies with royal pawns.

### Resource drop
|  | Steel drop | Wood drop | Leather drop | Chemfuel drop | Neutroamine drop | Bioferrite drop |
|---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Value | 475 ($250*1.9$) | 480 ($400*1.2$) | 472 ($225*2.1$) | 460 ($200*2.3$) | 480 ($80*6$) | 450 ($600*0.75$) |
| Title | Acolyte | Acolyte | Acolyte | Knight | Knight | Knight |

The new drops are almost identical to steel drop and share the same row in the permit menu. They have no permit prerequisites. The goal is to make acquiring a royal title more attractive for players who may not have abundant access to trees or wild animals (deserts, ice sheet, etc). They are balanced around market value, not subjective value.

### Valuable resource drops
|  | Silver drop | Gold drop | Archite Capsule drop | Gravlite drop |
|---:|:---:|:---:|:---:|:---:|
| Value | 500 | 750 ($75*10$) | 600 ($3*200$) | 600 ($150*4$) |
| Cooldown | 45 | 60 | 60 | 60 |
| Title | Knight | Praetor | Praetor | Praetor |
| Favor | 6 | 8 | 8 | 8 |

A Grand Meditation Throne costs 75 gold, and is required (for the first time) to rank up from Praetor to Baron. Gold drop will provide the most value at this rank. I think this adds a lot of value, especially for people who can't mine gold or haven't won the orbital trader RNG war, without feeling OP or out of place.