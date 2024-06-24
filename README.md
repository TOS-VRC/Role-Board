# Town of Salem VRC Role Board
This is the information used for the role cards in the [VRChat](https://vrchat.com/) **Town of Salem** world by [miner28_3](https://vrchat.com/home/user/usr_8b3d0e61-3178-4277-a9e2-a3aa9e6e6b7d).

**World ID:** [wrld_42d023dc-1b2d-439a-b741-09113ca0e59a](https://vrchat.com/home/launch?worldId=wrld_42d023dc-1b2d-439a-b741-09113ca0e59a)

**Discord server:** [discord.gg/tosvrc](https://discord.gg/tosvrc/)

## Syntax
The information is written in JSON.
##### roles.json
The JSON values should be easy to understand.
``` JSON
[
  {
    "name": "Drunk",
    "alignment": "Town",
    "alignmentType": "Chaos",
    "attack": "None",
    "defense": "None",
    "abilities": "Do nothing at night.",
    "attributes": "Be drunk.",
    "goal": "Get sober or die trying.",
    "classicResults": "Sheriff, Executioner, Werewolf or Drunk",
    "covenResults": "",
    "additional": "test line 1\ntest line 2",
    "dlc": false,
    "unique": false,
    "community":true,
    "color":null
  },
  {
    "name": "",
    "alignment": "",
    "alignmentType": "",
    "attack": "",
    "defense": "",
    "abilities": "",
    "attributes": "",
    "goal": "",
    "classicResults": "",
    "covenResults": "",
    "additional": "",
    "dlc": false,
    "unique": false,
    "community":true,
    "color":null
  }
]
```
##### rolelists.json
The `variations` value is a list of lists. Each list in the list has a length equal to the number of players in the rolelist, and each value in the list is matched to a list of role IDs. See: [roles.txt](roles.txt)
``` JSON
[
   {
      "name": "City of Lights",
      "dlc": true,
      "variations": [
         [21, 18, 18, 33, 17, 23, 23, 3, 3, 3, 62, 62, 59, 59, 59]
      ]
   },
   {
      "name": "Classic",
      "dlc": false,
      "variations": [
         [21, 19, 18, 17, 26, 27, 29, 4, 0, 36, 37, 44, 60, 55, 56],
         [21, 19, 18, 17, 26, 27, 29, 4, 0, 36, 37, 44, 60, 55],
         [21, 19, 18, 17, 26, 29, 4, 0, 36, 37, 44, 60, 56],
         [21, 19, 17, 26, 29, 4, 0, 36, 37, 44, 60, 55],
         [21, 19, 17, 26, 29, 4, 0, 36, 37, 44, 60],
         [19, 17, 26, 29, 4, 0, 36, 37, 5, 56],
         [19, 17, 26, 29, 4, 0, 36, 37, 60],
         [17, 26, 27, 4, 0, 36, 37, 55],
         [17, 26, 27, 4, 0, 36, 37]
      ]
   }
]
```

## Editor
A small editor tool exist to preview and edit the information.

Download: [Editor.zip](https://cdn.discordapp.com/attachments/775695682484043788/945273652482568232/RoleEditor.zip)
