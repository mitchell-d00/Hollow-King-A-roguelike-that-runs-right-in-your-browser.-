<p align="center"><img src="logo.svg" width="96" alt="Hollow King logo"></p>

# Hollow King

A roguelike in a single HTML file. Pick one of six classes, fight down through
twenty procedurally generated floors, and kill the Hollow King at the bottom.
Death is permanent.

## Play

Open `index.html` in any browser. There is nothing to install or build.

To put it online, turn on GitHub Pages for this repository (Settings → Pages →
deploy from the `main` branch, root folder). The game will be served at
`https://<your-username>.github.io/<repo-name>/`.

The game saves in the browser each time you take the stairs. A save is deleted
when the character dies or wins.

## What is in it

- **6 classes**: Warrior, Rogue, Mage, Cleric, Ranger and Paladin, each with
  four abilities learned at levels 1, 5, 12 and 20.
- **30 character levels.** Each level raises two attributes for your class and
  gives one point to spend yourself.
- **200 items**: 60 weapons, 40 pieces of armour, 15 rings, 10 amulets,
  15 potions, 15 scrolls, 10 wands, 5 foods, 10 gems and 20 one-of-a-kind
  artifacts.
- **100 kinds of monster**, five for each of twenty monster levels, with traits
  such as fast, slow, ranged, spellcasting, poisonous, mana-draining, thieving,
  regenerating and undead.
- **20 floors**, a new layout every game, with the Hollow King on the last.
- **Gold and shops.** Shopkeepers stand on the map on every odd floor:
  apothecaries, armourers and curio dealers. Walk into one to buy and sell.
- **A character sheet** showing attributes, combat numbers, equipment in nine
  slots and abilities, where you also spend attribute points.

## Controls

| Action | Keys |
| --- | --- |
| Move or attack | Arrow keys, or W A S D; Q E Z C for diagonals |
| Wait a turn | Period |
| Abilities | 1 to 4 |
| Fire a ranged weapon | F |
| Explore automatically | X |
| Rest until healed | R |
| Take or walk to the stairs | Enter or > |
| Pack | I |
| Character sheet | P |
| Close a window | Escape |

Click a monster to target it, or click the map to step that way. On a touch
screen a direction pad and action buttons appear under the map.

## How the numbers work

- **Strength** adds melee damage, **Dexterity** adds accuracy, evasion and
  ranged damage, **Intellect** adds mana and spell power, **Vitality** adds
  health. Daggers and short swords use Dexterity for damage when it is higher.
- Armour reduces physical damage by a proportion; spells from monsters are
  reduced much less.
- Sleeping monsters are always hit, and a Rogue's Backstab does far more to
  them.
- Gems do nothing except sell well.

## Files

- `index.html` — the whole game: markup, styles, data and script
- `logo.svg` — repository logo and page icon
- `LICENSE` — MIT licence

## License

MIT. See `LICENSE`.
