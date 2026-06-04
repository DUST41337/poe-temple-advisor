# PoE2 Temple Advisor

A static browser tool for planning Path of Exile 2 Temple of Atziri boards.

Open the app: https://dust41337.github.io/poe-temple-advisor/

## Use

Open the GitHub Pages URL above and edit the board in your browser. The app
runs entirely as static HTML/CSS/JavaScript.

Select a room card in the palette to highlight recommended placement cells.
The strongest candidate is shown in gold, followed by good and okay options.
Cards place only the room type. Room Tier is inferred from adjacent room-card
influence and highlighted on the board, so higher-Tier displays are
board-derived instead of manual right-click overrides.

## Privacy model

Board edits are saved only in the current browser with `localStorage`.

- The GitHub repository stores the shared app files.
- Personal board data is not uploaded to GitHub.
- Different users have separate browser-local data.
- Clearing browser site data can remove saved boards.

Use Board JSON export/import when you want a manual backup or to share a board.

## Notes

Icons are local schematic symbols for planning and are not copied game assets.
English and Japanese room names are aligned with PoE2DB's Atziri's Temple
room list:
https://poe2db.tw/us/Atziris_Temple#Rooms
https://poe2db.tw/jp/Atziris_Temple#Rooms
