# China Map 中国地图

A mobile-friendly game for learning the map of China in Chinese: provinces, 简称 (short names), capitals, regions and neighbouring provinces. It also shows Singapore Changi's nonstop routes to 36 Chinese cities and the airlines that fly them.

**Play:** https://eadgpt.github.io/china-map/

## Modes

- **训练 Train**: the main game. Turn every province gold. Questions get harder as you level up a province (find it → name & 简称 → capital & neighbours), and your weakest provinces come up most often.
- **探索 Explore**: search or tap any province or city for its Chinese name, pinyin, 简称, capital, region, neighbours and Changi routes. The Layers button switches labels, regions, all cities and Changi routes.
- **拖放 Place**: drag names, 简称, capitals or regions onto a blank map.
- **樟宜 Changi**: find the 36 Changi-connected cities.

The Train tab has two tracks: **省份 Provinces** and **城市 Cities**. The city track covers all 332 prefecture-level cities (地级市, 自治州, 地区, 盟), and you can filter it by region. Explore shows every city, and names appear as you zoom in.
- **航空 Airlines**: Chinese airline short names (国航, 东航, 南航…), groups, bases and who flies from Singapore.

Designed mobile-first in an iOS style, with dark mode, a bottom sheet, smooth zoom and small animations (reduced when the device asks for less motion).

Tap **?** at the top for a guided tour of every button on the current screen.

## Notes

- Everything is in one file, `index.html`. No build step.
- Progress is saved in your browser only (localStorage).
- Route data as of 3 Nov 2026. Airline groups and bases are a study aid; verify before citing.
- Map shapes from the Apache ECharts China map (Apache-2.0).
