# lab_FDI_trade
Lab code for Global Macro Data Analysis for Public Policy, Spring 2026
## Assignment: Top 10 US Export Destinations, 2015 vs 2025

This analysis uses the Census Bureau international trade API (exports/naics endpoint) to pull total US exports by destination country, then ranks the top 10 destinations for 2015 and 2025. See `lab_FDI_trade.R` for the code and `top10_exports_2015_2025.png` for the graph.

### What changed, 2015 → 2025

The most notable shift is what *didn't* happen to China. China held the #3 spot in both years, but that stability is misleading: its value as a destination for US exports barely moved (roughly $115B to $108B), actually declining in nominal terms while every other top partner grew. After adjusting for inflation, US exports to China meaningfully contracted. Over the same period, Mexico overtook Canada for the #1 position and both surged well past $300B, so China didn't just stand still — it fell sharply in relative importance.

The likely driver is the breakdown in the US-China trade relationship since 2018: tariffs and Chinese retaliation against US goods, followed by export controls on semiconductors and advanced technology. As trade with China stagnated, US exports redirected toward neighbors and allies — Mexico and Canada through nearshoring and USMCA, and newcomers like Taiwan and the Netherlands, whose entry into the top 10 tracks the growing importance of allied technology supply chains.