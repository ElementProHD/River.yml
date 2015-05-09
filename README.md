info:
  title: 'River'
  world: 'River'
  version: '1.0'
  type: 'dtm'
  creators:
  - 'ElementProHD'
  duration: 3600
  spawn: 476,6,-1365,0,-10
  time: 6000
teams:
 red:
  title: 'Red'
  spawn: 453.5,6,-1352,-90,10
  max: 10
  monuments:
  a:
   name: 'Blue'
   location: 453.5,8,-1368.5
  b:
   name: Orange
   location: 453.5,8,-1334.5
 green:
  title: Green
  spawn: 501.5,6,-1351.5,90,10
  max: 10
  monuments:
  a:
  name: Lime
  location: 501.5,8,-1334
  b:
  name: Yellow
  location: 501.5,8,-1368.5
loadout:
 helmet:
  item: leather helmet
 1:
  item: iron sword
 2:
  item: bow
 3:
  item: golden apple
  amount: 3
 4:
  item: bread
  amount: 32
 5:
  item: stone
  amount: 32
 6:
 item: iron axe
 enchants:
 - dig_speed:3
 7:
  item: glass
  amount: 32
 8:
  item: bucket
 27:
  item: arrow
  amount: 32
 28:
 item: arrow
 remove-drops:
 - iron sword
 - leader helmet
repair-drops:
- stone sword
- bow
- iron axe
- diamond pickaxe
regions:
  red-spawn:
  type: cylinder
  center: 453.5,6,-1352,-90,10
  radius: 5
  height: 4
  flags:
    build:
       who: '*'
       message: '&cYou may not edit Red team's base!'
  blue-spawn:
  type: cylinder
  center: 453.5,6,-1352,-90,10
  radius: 5
  height: 4
  flags:
    build:
       who: '*'
       message: '&cYou may not edit Blue team's base!'
