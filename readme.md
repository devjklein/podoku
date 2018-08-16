# Podoku 1.0.0
## Play now here: [https://devjklein.github.io/podoku/](https://devjklein.github.io/podoku/) ##

## CHANGELOG ##
### Version 1.0.0 (2018-08-15) "Public Release"
+ Polished phrasing
+ Fixed bug where clicking New Game after an invalid import still incremented the Current Game number
### Version 0.9.4 (2018-06-15) "Player data export"
+ Added support for exporting/importing player data to/from disk (519 lines now)
+ Major code optimization (2018-06-14); condensed functions, eliminated redundant functions, added better variable names and comments
+ Went from 478 lines of code to 408 before adding import/export function
+ Fixed bug where width: 100% and position: relative on html, body, main prevented user from clicking to place cards on table in Firefox

### Version 0.9.3 (2018-06-13) "Evil Undo Button"
+ Added undo button
+ Added best/average score panel with support for future leaderboard
+ Added current game counter
+ Added some <strong> tags to key information

### Version 0.9.2 (2018-06-12) "Podoku Beta"
+ Initial Beta release of Podoku
+ Help button
+ Instant scoring feedback
+ Player "Level" ranking
+ Draggable cards

## RESOURCES ##
**Several excellent articles and code snippets from around the web that were helpful in building this program.**

+ Pure JavaScript poker hand analyzer : [http://www.emanueleferonato.com/2015/09/18/pure-javascript-poker-hand-analyzer-update-fixing-ace-straight-and-commeting-the-code/](http://www.emanueleferonato.com/2015/09/18/pure-javascript-poker-hand-analyzer-update-fixing-ace-straight-and-commeting-the-code/)
+ Generate a deck of cards in JavaScript: [https://stackoverflow.com/a/32770132](https://stackoverflow.com/a/32770132)
+ Drag and drop with jQuery: [https://www.elated.com/articles/drag-and-drop-with-jquery-your-essential-guide/](https://www.elated.com/articles/drag-and-drop-with-jquery-your-essential-guide/)
