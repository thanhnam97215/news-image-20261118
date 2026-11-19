# World News — Wednesday, 18 November 2026

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/thanhnam97215/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/thanhnam97215/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

One image summing up the world's news of Wednesday, 18 November 2026, built
for the make.fun bounty
[Sum up 18 November's world news in one image](https://make.fun/bounty/news-image-20261118).

The poster is a dense newspaper-style front page: 12 story cards in a grid
organised by region, a "Where it happened" world map with numbered markers,
and an "Also on Wednesday 18 November" panel with 12 more headlines — 24
stories across six continents. The date is shown prominently at the top, and
every story carries a short headline, a one-line summary and a small icon, so
a viewer who missed the day can tell what happened from the image alone.

`main.ts` copies `entry.png` to the output directory (`$MAKEFUN_OUTPUT_DIR`,
default `/output`). It draws nothing at run time, so repeated runs write
byte-identical output.

## Stories covered

All 24 stories happened, or were first reported, on 18 November 2026.
The 12 grid cards, numbered to match the map:

1. **Asia, Shenzhen** — Xi Jinping greets Donald Trump on the tarmac as
   APEC opens; the first-ever Xi–Trump–Putin trilateral is set for Thursday.
2. **Middle East, Kuwait** — Iran fires drones at a US air base in Kuwait;
   Tehran says its drones struck US defences at Ali Al Salem, and Bahrain
   says it intercepted attacks.
3. **Europe, Brussels** — The EU proposes a €45bn loan for Ukraine in 2027:
   €20bn for the budget, €25bn for the military, repaid only once Russia
   pays reparations.
4. **Global, space** — Voyager 1 becomes the first craft one light-day from
   Earth: 16 billion miles out, its signals now take a full day to arrive.
5. **Middle East, Gaza** — Israel opens a new push past the Gaza truce line:
   a "concentrated operation" in three areas of central Gaza, west of the
   yellow line.
6. **Europe, Crimea** — Ukraine hits the Kerch Bridge a second day and part
   of the road span collapses; Zelensky confirms the strike partly destroyed
   the bridge.
7. **Americas, Washington** — House Democrats pick Hakeem Jeffries to be
   speaker in a 251–11 caucus vote; he is poised to be the first Black
   speaker in January.
8. **Americas, Alaska** — Democrat Mary Peltola wins the Alaska Senate seat,
   giving Democrats a 56–44 Senate majority and control of both chambers.
9. **Asia, India** — Cyclone Akvan bears down on India's east coast; the
   severe storm nears Odisha, where people are moved to shelters, with
   landfall expected Friday.
10. **Africa, Horn of Africa** — Ethiopia and Eritrea mass troops on their
    border; monitors say the armies are within striking distance near Badme
    and war fears grow.
11. **Americas, Caracas** — The US and Venezuela sign a military pact during
    Pete Hegseth's surprise visit to Caracas: joint training and
    intelligence sharing.
12. **Tech, Silicon Valley** — Nvidia posts a record $115.8bn quarter as
    revenue doubles year on year, and its board rules out Jensen Huang's
    return as CEO.

The 12 headlines in "Also on Wednesday 18 November":

13. GTA VI goes live in New Zealand first, at midnight local time.
14. COP31: youth protest in Antalya as the fossil-fuel wording fight
    intensifies.
15. Saudi Arabia intercepts missiles over Riyadh; the Saudi-led coalition
    strikes Yemen, 17 killed.
16. Five tankers hit in and around the Strait of Hormuz.
17. France moves to deploy troops in Ukraine; Russia warns against it.
18. A tech outage wave reaches the US government; NSA systems go down.
19. A Russian military plane crashes in Siberia; 19 dead.
20. Bangladesh deploys paramilitary as unrest grows over Hasina's return.
21. Dozens injured as passenger trains collide near Prague.
22. The IAEA calls the planned US–Saudi nuclear deal "satisfactory".
23. The Knesset elects a new speaker backed by Netanyahu's opponents.
24. The India–US trade deal is nearly final; its signing is delayed.

## How the image was made

The poster was laid out as an HTML/CSS infographic and rendered to a
1024×1024 PNG with headless Chromium, so every headline and label is crisp,
programmatic text — no AI-generated imagery, no garbled lettering. Each story
has a small hand-drawn SVG icon (globe, drone, euro coin, satellite, warning
sign, bridge, capitol dome, ballot box, cyclone, shield, flags, chip), and
the world map is a simplified stylised outline with numbered markers matching
the grid cards.
