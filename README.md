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

investigating:
- additional permits
- vanilla permit rebalance
- new scenario and a player faction

## Analysis
### Awarded permit points
The vanilla permit point progression is Acolyte + 1 -> Knight + 1 -> Praetor + 1 -> Baron + 1 -> Archon +1 -> 5 total permit points.\
I like the idea of resticting colonists to one or two trees, but the new additions call for more points. Baron now awards 2 points for a total of 5 for Barons and 3 points for Archons for a total of 8. This should retain a tighter permit tree in the early game while awarding more freedom in the late game.

### Combat drop
|  | Charge rifle drop | Prestige armor drop |
|---:|:---:|:---:|
| Value | 1010 | 2690 ($1975+715$) |
| Cooldown | 60 | 150 |
| Daily value | 16.8 | 17.9 |
| Favor | 10 | 22 |

Both of these drops require an Archon. The prestige armor drop is a prestige recon armor set with a helmet. Since it's a late-game permit, and the player has presumably already met the armor requirements for their royal pawn, this is balanced to make honor quest rewards more attractive for colonies with Archons. It's not dramatically more valuable than other permits when you consider daily value with cooldowns or the honor to market value ratio.

For example, the vanilla food drop has an honor:market value ratio of 120. The charge rifle drop is 101. The prestige armor drop is 122.

With Combat Extended, the charge rifle drop comes with 300 6x24mm rounds. This increases the daily value to 19.3 and the honor:market value ratio to 116.

### Food drop
|  | Food drop | Fine food drop | Lavish food drop |
|---:|:---:|:---:|:---:|
| Food type | Packaged survival meal | Fine meal | Lavish meal |
| Value | 480 ($20*24$) | 400 ($20*20$) | 800 ($20*40$) |
| Cooldown | 45 | 45 | 60 |
| Title | Acolyte | Acolyte | Baron |
| Favor | 4 | 4 | 8 |
| Daily value | 10.6 | 8.88 | 13.3 |

The new food drops are meant to satisfy title requirements, whereas the vanilla food drop is a general food solution for the colony. Fine meals are required for Acolyte+ colonists, and lavish meals are required for Baron+. Since this is meant to prevent mood debuffs for a short period of time, I didn't balance for market value.

### Glitterworld med drop
This only provides 5 medicine, worth 250 silver. It's great for single-pawn emergencies, but anyone with colonies of 12+ (reasonable considering the Baron title) will find it lacking for something like a malaria outbreak. I've upped it to 10 and increased the cooldown to 60 days. It's a negligble net daily value increase (5.55 -> 8.33).

### Gold/silver drop
|  | Silver drop | Gold drop |
|---:|:---:|:---:|
| Value | 500 | 750 ($75*10$) |
| Cooldown | 45 | 60 |
| Title | Knight | Praetor |
| Favor | 6 | 8 |

A Grand Meditation Throne costs 75 gold, and is required (for the first time) to rank up from Praetor to Baron. Gold drop will provide the most value at this rank. I think this adds a lot of value, especially for people who can't mine or haven't won the orbital trader RNG war, without feeling OP or out of place.

### Resource drop
|  | Steel drop | Wood drop | Leather drop |
|---:|:---:|:---:|:---:|
| Value | 475 ($250*1.9$) | 480 ($400*1.2$) | 472 ($225*2.1$) |

Leather drop (plainleather) and wood drop are almost identical to steel drop, and share the same row in the permit menu. They have no permit prerequisites. The idea is to provide more value to players who may not have great access to trees or wild animals (deserts, ice sheet, etc). They are balanced around market value, not subjective value. 400 wood would have almost no impact on a colony in the rainforest, but could prevent a sea ice colony from freezing to death for a short period of time.