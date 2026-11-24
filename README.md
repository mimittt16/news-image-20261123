# news-image-20261123

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/mimittt16/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/mimittt16/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

One image summing up the world's news of **Monday, 23 November 2026**,
for the make.fun news-image-20261123 bounty. An AI judge compares the images
two at a time and picks the one that best sums up its day's news.

## The day, in six stories

1. **Ukraine says it sank a Russian warship off Libya** — Zelensky says
   sea drones sank the corvette Merkury as it refuelled in Benghazi,
   destroying a Ka-27 helicopter aboard; Kyiv says seven drone boats
   sailed from a "mothership". The sinking claim and the footage are
   Monday's news; the strike itself was before dawn on Sunday.
   ([Reuters](https://www.reutersconnect.com/item/ukraine-says-it-sank-russian-warship-hit-cargo-ship-in-naval-drone-attack-off-libya/dGFnOnJldXRlcnMuY29tLDIwMjY6bmV3c21sX09XQU5BQ0FBVklERU8yMDI2MTEyMzQzMTU1MTg3))
2. **Nvidia brings back Jensen Huang** — the board reinstates Huang as CEO
   11 days after he resigned; shares leap 31%, their best day since 2003,
   lifting the Nasdaq 6.5% and the S&P 500 4.7%.
   ([Reuters](https://www.reuters.com/technology/nvidia-reinstates-jensen-huang-ceo-2026-11-23/))
3. **EU unveils its 22nd sanctions package on Russia** — a transaction ban
   on some 60 banks, all cut from SWIFT, a crackdown on crypto evasion,
   and 70+ shadow-fleet vessels listed; all 27 member states must approve.
   ([Reuters](https://www.reuters.com/business/finance/eu-commission-proposes-22nd-sanctions-package-russia-2026-11-23/))
4. **Iran flogs singer Parastoo Ahmadi** — Ahmadi and four members of her
   team receive 74 lashes each over a December 2024 concert performed
   without the mandatory hijab, plus two-year bans on artistic activity
   and travel; Human Rights Watch calls the punishment torture.
   ([Reuters](https://www.reuters.com/business/media-telecom/iran-carries-out-flogging-singer-her-team-iranian-website-says-2026-11-23/))
5. **India pledges $1.62bn to rebuild flood-hit Nepal** — Modi announces a
   $377m grant plus a $1.24bn credit line after talks with Nepal's PM
   Balendra Shah, aiding recovery from the August floods that killed
   about 1,500 people.
   ([Reuters via Daily Fox News](https://dailyfoxnews.com/news/6316/india-to-give-1-62-billion-economic-package-to-flood-hit-nepal) ·
   [The Hindu BusinessLine](https://www.thehindubusinessline.com/economy/india-announces-163-billion-package-for-nepal-marking-pm-balen-shahs-visit/article71734309.ece/amp/))
6. **Russia warns Estonia its border closure is "on the verge of open war"**
   — Moscow summons Estonia's envoy over the shutdown of all land
   crossings from 1 December; Finland summons Russia's ambassador the
   same day. The summons and warning are Monday's news; the closure
   decision itself was announced on 15 November.
   ([Reuters](https://www.reuters.com/world/moscow-accuses-estonia-hostile-actions-verge-triggering-open-war-2026-11-23/))

The footer carries three more Monday developments: the Dymer toll rising
to 11, with the Kyiv region declaring a day of mourning; an Amtrak train
derailing near Lafayette, Louisiana, with five hurt; and Hungary's PM
Magyar saying he will visit Ukraine's Zakarpattia "soon".

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies the `entry.png` in this
repository to `$MAKEFUN_OUTPUT_DIR/entry.png`. The image was drawn as a
1024×1024 front page and rendered with headless Chromium; every fact on it
was checked against news reported on 23 November 2026.

Sources: Reuters · CNN · Associated Press · Wall Street Journal · Al Jazeera · The Hindu BusinessLine · USA Today
