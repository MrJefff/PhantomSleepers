If you've ever needed a player to hide in a location to lure someone you suspect of using ESP then this tool is for you.

It is recommended that you bind the console command to a key, or change the name of the console command to something more convenient. (in your client console type: bind p createphantom)

This tool is for admins only.

View the item list here [Oxide API for Rust](http://docs.oxidemod.org/rust/#item-list)

## Console Command
- `createphantom` -- will spawn a phantom player at the position you are looking at. This phantom is automatically given clothing, a weapon, and put to sleep. All items spawned are given random skins to make the sleeper look as unique as possible.

## Configuration

- Invisbility - Hide Real Sleepers (default: disabled) - Make the real sleeper invisible so real ESP hackers do not see two players with duplicate names.

- Strip Phantoms On Death (default: enabled) - Strip all items from the phantom when it dies.

- Destroy Phantom Corpses (default: enabled) - Despawn phantom corpses when they spawn.

- Prevent Phantom Looting (default: enabled) - Prevent all players from looting phantoms.

- Console Command (default: createphantom) - Console command name to create a phantom sleeper.

- Max Raycast Distance (default: 100f) - Default maximum distance to find a position.

- Min Distance From Real Sleeper (default: 450f) - The minimum distance which the real sleeper must be from the phantom sleeper.

- Random Names (none) - Using this option will select a random name from this list instead of chosing from a random sleeper on your server. e.g: "billy the kid", "infinity's edge", "sams"

- Gear - See config.
