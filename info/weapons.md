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

| | ATK | P | Cost | Location |
| :-- | --: | --: | --: | :-- |
| Hammer | 10 | 1 | | Mushroom Way |
| NokNok Shell | 20 | 2 | | Midas River |
| Punch Glove | 30 | 3 | 36 | Moleville |
| Masher | 50 | 30 | | Booster's Tower |
| Super Hammer | 40 | 4 | 70 | Marrymore |
| Troopa Shell | 50 | 5 | 90 | Seaside Town |
| Mega Glove | 60 | 6 | 102 | Nimbus Land |
| Ultra Hammer | 70 | 7 | | Factory |
| Lazy Shell | 90 | 40 | | Rose Town |
| Hammer | 0 | 0 | 123 | Seaside Town |
