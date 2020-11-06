# genshin impact id api

### information is based on version 1.0.1 from the fandom and various others.
### roast my shitty code or contribute here [github.com/LichKing112/gi-id-api](https://github.com/LichKing112/gi-id-api)


## Todo
- [ ] add support for different language
- [ ] birthdays for characters
- [ ] add skills
- [ ] add talents
- [ ] add constellation
- [ ] add cooking/ingredients
- [ ] add artifacts
- [ ] add domains
- [ ] add materials
- [ ] add potions/consumables before that other npm library finishes it
- [ ] add mobs
- [ ] add achievements
- [ ] add commissions
- [ ] add function to get lists. simple/verbose
- [ ] add scaling calculators
- [ ] move the checklist to wiki or docs folder
- [ ] cleanup readme
- [ ] add fuzzy search support
- [ ] ground pound ur mom
- [ ] fix typo with otherworldly story file name
- [ ] lore???
- [ ] npc???
- [ ] license?
- [ ] pretend to add tests
- [ ] add banner history maybe

## characters
- [x] amber
- [x] barbara
- [x] beidou
- [x] bennett
- [x] chongyun
- [x] diluc
- [x] jean
- [x] fischl
- [x] kaeya
- [x] keqing
- [x] klee
- [x] lisa
- [x] mona
- [x] ningguang
- [x] noelle
- [x] qiqi
- [x] razor
- [x] sucrose
- [x] traveler
- [x] venti
- [x] xiangling
- [x] xingqiu

## - elements
- [x] anemo
- [x] cryo
- [x] dendro
- [x] electro
- [x] geo
- [x] hydro
- [x] pyro

## - swords
- [x] skywardblade
- [x] aquilafavonia
- [x] blackclifflongsword
- [x] royallongsword
- [x] thealleyflash
- [x] favoniussword
- [x] theblacksword
- [x] theflute
- [x] sacrificialsword
- [x] prototyperancour
- [x] lionsroar
- [x] ironsting
- [x] swordofdescension
- [x] skyridersword
- [x] filletblade
- [x] travelershandysword
- [x] harbingerofdawn
- [x] darkironsword
- [x] coolsteel
- [x] silversword
- [x] dullblade


## - claymores
- [x] skywardpride
- [x] wolfsgravestone
- [x] sacrificialgreatsword
- [x] thebell
- [x] lithicblade
- [x] blackcliffslasher
- [x] serpentspine
- [x] whiteblind
- [x] royalgreatsword
- [x] rainslasher
- [x] prototypeanimus
- [x] favoniusgreatsword
- [x] skyridergreatsword
- [x] quartz
- [x] whiteirongreatsword
- [x] ferrousshadow
- [x] debateclub
- [x] bloodstainedgreatssword
- [x] oldmercspal
- [x] wastergreatsword

## - bows
- [X] amosbow
- [x] skywardharp
- [x] compoundbow
- [x] blackcliffwarbow
- [x] theviriescenthunt
- [x] prototypecrescent
- [x] sacrificialbow
- [x] alleyhunter
- [x] rust
- [x] thestringless
- [x] royalbow
- [x] favoniuswarbow
- [x] sharpshootersoath
- [x] slingshot
- [x] ravenbow
- [x] ebonybow
- [x] messenger
- [x] recurvebow
- [x] seasonedhunterbow
- [x] huntersbow


## - catalysts
- [x] skywardatlas
- [x] lostprayertothesacredwinds
- [x] eyeofperception
- [x] blackcliffamulet
- [x] favoniuscodex
- [x] mappamare
- [x] prototypemalice
- [x] royalglimoire
- [x] sacrificialfragments
- [x] solarpearl
- [x] thewidsith
- [x] wineandsong
- [x] twinnephrite
- [x] ambercatalyst
- [x] thrillingtalesofdragonslayers
- [x] magicguide
- [x] emeraldorb
- [x] otherworldystory
- [x] pocketgrimoire
- [x] apprenticesnotes

## - polearms
- [x] primodialjadewingedspear
- [x] kunwusirisrift
- [x] skywardspine
- [x] crescentpike
- [x] blackcliffpole
- [x] dragonsbane
- [x] prototypegrudge
- [x] deathmatch
- [x] lithicspear
- [x] favoniuslance
- [x] blacktassel
- [x] whitetassel
- [x] halberd
- [x] ironpoint
- [x] beginnersprotector


-------------------------------------

```js
const genshin = require('gi-api-id')
 
console.log(genshin.characters('amber'))
```

```json
{
    "name": "Amber",
    "titles": [
        "Outrider",
        "Champion Glider"
    ],
    "element": "Pyro",
    "weapon": "Bow",
    "gender": "Female",
    "region": "Mondstadt",
    "rarity": "4",
    "images": {
        "image": "https://static.wikia.nocookie.net/gensin-impact/images/c/c6/Character_Amber_Thumb.png",
        "card": "https://static.wikia.nocookie.net/gensin-impact/images/2/26/Character_Amber_Card.jpg",
        "potrait": "https://static.wikia.nocookie.net/gensin-impact/images/0/00/Character_Amber_Portrait.png"
    },
    "cv": {
        "japanese": "Manaka Iwani",
        "korean": "Kim Yeon-woo",
        "chinese": "Tingting Hu"
    },
    "affiliation": "Knights of Favonius",
    "description": "A perky, straightforward girl, who is also the only Outrider of the Knights of Favonius. Her amazing mastery of the glider has made her a three-time winner of the Gliding Championship in Mondstadt. As a rising star within the Knights of Favonius, Amber is always ready for any challenging tasks.",
    "url": "https://genshin-impact.fandom.com/wiki/Amber"
}
```

or

```js
const genshin = require('gi-api-id')
 
console.log(genshin.elements('anemo'))
```

```json
{
    "name": "Anemo",
    "type": "Wind",
    "color": "#a8f5ce",
    "emoji": "<:Element_Anemo:763984819066634289>",
    "region": "Mondstadt",
    "archon": "Barbatos",
    "theme": "Germany",
    "url": "https://static.wikia.nocookie.net/gensin-impact/images/a/a4/Element_Anemo.png"
}
```
