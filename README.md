# ftb_quest_explorer

A browser-based visualizer for FTBQuest QuestBook for minecraft. Load your Modpack and instantly see every quest in the pack.
For questbook from : https://docs.feed-the-beast.com/mod-docs/mods/suite/Quests/

No server required — open `snbt.html` directly in your browser or serve it with any static file server.


---
## Web UI

![Imgur](https://imgur.com/7Mt8KSW.jpg)
![Imgur](https://imgur.com/HsYkJuA.jpg)
![Imgur](https://imgur.com/tuO7c9K.jpg)

---

## Usage

1. Open `snbt.html` in a browser (Chrome / Firefox / Edge — any browser with ES module support).
2. Click **Load files** and select the `.zip` produced by the pack author.
3. Explore the rendered image for each quests, the layout try to be as close the the ingame experience (See Notes)
4. Have fun playing !!

---

## Getting files

1. Go to https://www.curseforge.com/minecraft/search?class=modpacks&page=1&pageSize=20&sortBy=relevancy
2. Download desired modpack to see its questbook content and choose the one you like.

---

## Debug mode

Append `?debug=1` to the URL before loading a file 

---

## Notes

 - The images for each item are not in the modpack files but in each and every mods themselves.
	some tools exists to see them : https://github.com/oparisblue/minecraft-textures-viewer
	its a little too much for my little hand and it cold take a lot off time to gaher all images.
	so, image that are rendered are in the modpack to ehance the questbook.
 - I'm not a professional programer and did this on my free time. Please be suggestive.