Bbuilt using **https://slint.dev/**

The game consists of a grid of 16 rectangular tiles. When clicking on a tile, an icon underneath is uncovered. We know that there are 8 different icons in total, so each tile has a sibling somewhere in the grid with the same icon. The objective is to locate all icon pairs. Only two tiles can be uncovered at the same time. If they are not the same, then the icons will be obscured again. We need to remember under which tiles the matching graphics are hiding. If two tiles with the same icon are uncovered, then they remain visible - they are solved.

![Slint Memory Game](https://github.com/goldhaxx/memory_game/assets/1616671/9df068e9-56dd-438a-bc9f-18f913738d38)
