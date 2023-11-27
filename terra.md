# terra
flow, build: dida365

TODO  
- [ ] keyboard & mouse  
  - E ~ F, H·J ~ C·V  
  - ~~W ~ E, A ~ S, S ~ D, D ~ F~~  
  - ~~E ~ R, R ~ Q~~  
  - ~~H ~ A, J ~ Z, B ~ B~~  
- [ ] build: platform(Ctrl), town, crafting, arena/fishery, biomes town  
- [ ] information accessories  
- [ ] storage: quick stack  
- [ ] item categories(chests)  
- [ ] respawn length: item, enemy  
- [ ] movement speed: mounts, wings, sprinting accessories, dash accessories  
- [ ] spawn rate: town, sun plants, peace/water candle, buff potions  
- [ ] recovery rate  
- [ ] souls farming(harvesting): underworld  
- [ ] fishery: spawn point(teleport), world renaming  
- [x] sand block: swap  
- [x] void bag, void vault  
- [x] mimics  
- [x] desert fossil: extractinator, sturdy fossil, scarab bomb  
- journey mode  
  - [ ] ~~scarab bomb: angle~~  
  - [x] research, duplication  
- [x] tmod: aimbot config, distance  

```yml
flow:


explore elements:
• ~: controller, mouse & keyboard
  ∘ ~: move, build/retrieval, interact(use, throw/discard, ···)
• spawn point: flag, wood/platform, ground flat, hike
• 1st PM 7:30:                                        #done
  ∘ house × 6: below ground level, spawn point
    • walls(hammer): retrieval from natural wall (staring by edge)
• build:
  ∘ base:
    • chamber: mining, hellevator
    • crafting station: target dummy
    • arena: out of spawn point screen
      ∘ ~: lava pit
      ∘ ~: peace candle, town
  ∘ t/p: town/pylon
                            t/p
    ocean·desert t/p-snow  forest desert-t/p jungle-t/p forest·ocean
                         hellevator
  ∘ fishery: blood moon, forest
• gather: pots, chests, npc, enemies/boss, mining
  ∘ coins: ~
  ∘ gem: amber
  ∘ ore/bar: iron/lead, gold/platinum
• merchant: bug net, iron anvil, mining helmet, wooden arrow, ···
• tools: pickaxes/drill
• class setup: weapons + armors+accessories, switching on demand #todo
  ∘ melee: umbrella, flail, sword; ···
  ∘ ranged: gun, bow(queen bee), grenade; ···
  ∘ magic: 
  ∘ summoner: 
• farms:                    #todo
  ∘ tree: flat, 3 tile
  ∘ herbs: tile(7 × 15 tiles), biomes(blocks,grass)
  ∘ fishing bait: buggy statue, shimmer
    • jungle grass: 3 × 15 tiles, half-screen
  ∘ gem farm: aether/shimmer, peace candle & sun plants, sticky bomb(throw up)
    • pylon: underg/cavern
  ∘ enemies(spawning): horiz chamber, water candle, potions(battle,luck)
• health: control, recovery
• mana: recovery
• defense:
• movement speed:
  ∘ mounts:                       #todo
  ∘ wings: enemies in space biome, harpies(feather), wyverns(soul of flight)
• events:
• boss:
• conversion: isolation(sun plants, 3 tiles)

biomes:
∘ surface, underg/cavern
  • forest
  • space
  • evil
  • desert
  • jungle
  • snow
  • ocean
∘ glow-mashroom
∘ dungeon
∘ underw

class setup:
• melee
• ranged
• magic
• summoner

weapons: damage, speed, scope
• melee: swords, yoyos, spears, boomerangs, flails, other
• ranged: bows&repeaters, guns, launchers, consumables grenades, others
• magic: wands, magic guns, spell books, others
• summoner: minion-summoning, sentry-summoning, whips
• others: placeable, explosives, others

item categories(chests):
• weapons
• armor
• vanity
• blocks
• furniture
• accessories
• equipment
• consumables
• tools
• materials: gem, ore, bar, souls
• misc

```