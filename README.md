[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
# Crawlit - Dofus & Dofus-Touch encyclopedia parser - Build your own Dofus API

In order to respond to a need expressed by the community, I create an encyclopedia parser for `Dofus` available for : </br>
- `Windows`
- `OSX` 
- `Linux`

**Download** : [All versions are available here](https://github.com/raczak/crawlit-dofus-encyclopedia-parser/releases)


**:warning: Don't use the tool for more than 20 pages per hour**

Crawlit was built to be very light full, it can run on almost every configurations.

In fact Crawlit is a tool :

- Developed by the dofus community, for the community
- **100% performance** : Developed to be very light full
- Simple to use | Plug and use
- English & French encyclopedia supported (french item & english item)

App launched           |  App at the end
:-------------------------:|:-------------------------:
![](https://raw.githubusercontent.com/raczak/crawlit-dofus-encyclopedia-parser/master/assets/crawlit1.JPG)  |  ![](https://raw.githubusercontent.com/raczak/crawlit-dofus-encyclopedia-parser/master/assets/crawlit6.JPG)

## JSON files also provided in the repository
In case you wan't directly the dofus JSON files, I oftenly upload up-to-date encyclopedia JSON in the `data/` folder.

## JSON format
An item result example
```json
{  
  "item_identifiant":"item ID",
  "name":"item name",
  "description":"item description.",
  "lvl":"item lvl",
  "type":"item type",
  "imgUrl":"image url of the item",
  "url":"Item's link",
  "stats":[ "many statistics line", "stat 2", ["..."], "stat n" ],
  "condition":[ "many conditions line", "condition 2", ["..."], "condition n" ],
  "set":{  
     "id":"set ID in order to link it with items (relation : one to many)",
     "url":"set url",
     "name":"set name"
  }
}
```

## App usage example
![](https://raw.githubusercontent.com/raczak/crawlit-dofus-encyclopedia-parser/master/assets/crawlit_API.gif)

## Technologies choice
Crawlit is build with full javascript : [NodeJs/Npm](https://nodejs.org/en/), javascript.

![](https://raw.githubusercontent.com/raczak/crawlit-dofus-encyclopedia-parser/master/assets/node-js.png)

## Bug & Crash || Proposal ?
For proposal don't hesitate to create a pool request or for a bug/crash an issue. You can also make us aware on [bugs channel in discord](https://discord.gg/r6nEaHp).

## Discord
[Click here to join the sosnoob community on discord !](https://discord.gg/8rKmXDd)

[<img src="https://raw.githubusercontent.com/raczak/crawlit-dofus-encyclopedia-parser/master/assets/discord-Logo.jpg">](https://discord.gg/8rKmXDd)


## Documentation(dev)
[Access the wiki to understand the project and contribute to it](https://github.com/raczak/crawlit-dofus-encyclopedia-parser/wiki/Dev-Documentation-(English)). [There is also a french version of the documentation](https://github.com/raczak/crawlit-dofus-encyclopedia-parser/wiki/Dev-Documentation-(Français)) :smiley: ! 

## Join the dev Team ?
[Contact us on discord](https://discord.gg/8rKmXDd) (channel general or private message to theukid)
