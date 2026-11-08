# China Map 中国地图

A mobile-friendly game for learning the map of China in Chinese: provinces, 简称 (short names), capitals, regions and neighbouring provinces. It also shows Singapore Changi's nonstop routes to 36 Chinese cities and the airlines that fly them.

**Play:** https://eadgpt.github.io/china-map/

## Modes

- **训练 Train**: the main game. Turn every province gold. Questions get harder as you level up a province (find it → name & 简称 → capital & neighbours), and your weakest provinces come up most often.
- **探索 Explore**: tap any province or city for its Chinese name, pinyin, 简称, capital, region, neighbours and Changi routes.
- **拖放 Place**: drag names, 简称, capitals or regions onto a blank map.
- **城市 Cities**: find the 36 Changi-connected cities.
- **航空 Airlines**: Chinese airline short names (国航, 东航, 南航…), groups, bases and who flies from Singapore.

## Notes

- Everything is in one file, `index.html`. No build step.
- Progress is saved in your browser only (localStorage).
- Route data as of 3 Nov 2026. Airline groups and bases are a study aid; verify before citing.
- Map shapes from the Apache ECharts China map (Apache-2.0).
