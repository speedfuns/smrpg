# Weapons

[Good guide for weapon mechanics, and the reference for this reference](http://www.gamefaqs.com/snes/588739-super-mario-rpg-legend-of-the-seven-stars/faqs/30935)

## Physical Damage Formula

`int(max(1,(PA + WP + rand(-P,P) - PD)) * T)`

- `int` = round down
- `max` = max integer from a list
- `rand` = random choice between two numbers

- `P` = `WP * 0.1`, with some exceptions
- `PA` = character's attack stat
- `PD` = enemy's defense stat
- `T` = timed attack multiplier (`1` untimed, `1.5` if timed correctly, or `2` if perfect)
- `WP` = weapon's attack stat

## Weapon Statistics

### Mario

| | ATK | P | Cost | Location | Notes |
| :-- | --: | --: | --: | :-- | :-- |
| Hammer | 10 | 1 | | Mushroom Way | Defeat Hammer Bros |
| NokNok Shell | 20 | 2 | | Midas River | After your first course |
| Punch Glove | 30 | 3 | 36 | Moleville | |
| Masher | 50 | 30 | | Booster's Tower | Thwomp see-saw in the first room |
| Super Hammer | 40 | 4 | 70 | Marrymore | |
| Troopa Shell | 50 | 5 | 90 | Seaside Town | |
| Mega Glove | 60 | 6 | 102 | Nimbus Land | |
| Ultra Hammer | 70 | 7 | | Factory | |
| Lazy Shell | 90 | 40 | | Rose Town | See Gardener with Seed and Fertilizer |
| Hammer | 0 | 0 | 123 | Seaside Town | "Lucky!" if timed correctly |

### Mallow

| | ATK | P | Cost | Location | Notes |
| :-- | --: | --: | --: | :-- | :-- |
| Froggie Stick | 20 | 2 | | Tadpole Pond | Get from Frogfucious |
| Cymbals | 30 | 3 | 42 | Moleville | |
| Whomp Glove | 40 | 4 | 72 | Marrymore | |
| Ribbit Stick | 50 | 5 | 86 | Seaside Town | |
| Sticky Glove | 60 | 6 | 98 | Nimbus Land | |
| Sonic Cymbals | 70 | 7 | | Bowser's Keep | Behind one of the Action Doors |

### Geno

| | ATK | P | Cost | Location | Notes |
| :-- | --: | --: | --: | :-- | :-- |
| Finger Shot | 12 | 3 | 50 | Moleville | |
| Hand Gun | 24 | 4 | 75 | Marrymore | |
| Double Punch | 35 | 5 | 88 | Seaside Town | |
| Hand Cannon | 45 | 6 | 105 | Nimbus Land | |
| Star Gun | 57 | 7 | | Bowser's Keep | Behind one of the Battle Doors |

### Bowser

| | ATK | P | Cost | Location | Notes |
| :-- | --: | --: | --: | :-- | :-- |
| Chomp | 10 | 4 | | Booster's Tower | Portrait puzzle |
| Chomp Shell | 9 | 3 | 75 | Marrymore | |
| Hurly Gloves | 20 | 5 | 88 | Seaside Area | |
| Spiked Link | 30 | 6 | 105 | Monstro Town | |
| Drill Claw | 40 | 7 | | Bowser's Keep | Behind one of the Battle Doors |

### Toadstool

| | ATK | P | Cost | Location | Notes |
| :-- | --: | --: | --: | :-- | :-- |
| Slap Glove | 40 | 4 | | Mushroom Kingdom | |
| Parasol | 50 | 5 | 75 | Seaside Town | |
| War Fan | 60 | 6 | 88 | Nimbus Land | |
| Super Slap | 70 | 7 | | Bowser's Keep | Behind one of the Action Doors |
| Frying Pan | 90 | 20 | 300 | Bowser's Keep | Behind one of the Battle Doors |
