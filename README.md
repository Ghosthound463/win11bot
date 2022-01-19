### Hi there 👋


**win11bot/win11bot** 

Win11 in React BOT

This Bot Account Runs the Deployment Preview for Windows 11 in react.

For the store please visit: https://github.com/win11bot/win11bot/tree/main/store

### To add your game/app 🎮

First make sure they accept iframe, you can check by inserting the url in this [iframe checker](https://www.tinywebgallery.com/blog/advanced-iframe/free-iframe-checker)

#### Either

#### 1. Create an [Issue](https://github.com/win11bot/win11bot/issues/new/choose) and follow the steps

### or

#### 2. Make a pull request by manually editing the store.json file

Read the schema below before adding any game/app element in the store file
```json
{
    "name": "Minecraft", // unique name (check if it has been used already in the file)
    "icon": "https://example.com/minecraft.png", // logo image, preferrably 1:1 and less than 128px of width
    "type": "game", // game or app
    "data": {
      "type": "IFrame", // type currently supports IFrame only
      "url": "https://classic.minecraft.net", // url of the app and make sure they accept Iframe
      "gallery": [ // three or more images for gallery view in store app
        "https://www.minecraft.net/content/dam/games/minecraft/key-art/CavesandCliffsPt1-dotNET-HomepagePromo-600x360.png",
        "https://variety.com/wp-content/uploads/2019/02/minecraft-best-year-yet.png?w=600",
        "https://www.minecraft.net/content/dam/games/minecraft/screenshots/RayTracing-MineCraft-PMP-Always-Something-New.jpg"
      ],
      "desc": "Minecraft is a sandbox construction video game ...", // description for store app
      "feat": "1.1 Combat changes.\n1.2 Fletching table functionality.", // features for store app
      "invert": true, // when true it forces dark theme for game/app window, default is false.
    }
  }
```
### PLEASE REMOVE THE COMMENTS FROM YOUR JSON, BEFORE MAKING A PR
**Comments look like this: `// example text`**

Add your game/app in the file (don't beautify the code, just add your game/app object) and make a pull request to get accepted.

# STOP SUGGESTING ANDROID GAMES

## Contributors
<a href="https://github.com/win11bot/win11bot/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=win11bot/win11bot" />
</a>****
