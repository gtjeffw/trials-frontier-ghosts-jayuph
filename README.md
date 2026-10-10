# Trials Frontier ghosts: jayuph

Best times and ghost replays of **jayuph** in Trials Frontier 7.9.0 (RedLynx/Ubisoft, iOS), whose online services have ended. A `trials-frontier-bundle` (format 1), made with [trials-frontier-patch](https://github.com/gtjeffw/trials-frontier-patch).

Published by [github.com/gtjeffw](https://github.com/gtjeffw), who states that **jayuph** is their own rider and these are their own runs. Every commit here was made through GitHub by that account and signed by GitHub (shown as Verified); check it with `python3 -I scripts/ghost_bundle.py verify gtjeffw/trials-frontier-ghosts-jayuph`.

- 222 best times, 113 ghosts (`ghosts/<leaderboard>.bin`, the game's own ghost files)
- rider hash `17FE8523` (the game's hash of the profile id; downloaded-opponent files are named after it), profile sha256 in the manifest
- 383 other riders' ghosts that the game downloaded as opponents (`others/<hash>/`)

## Use

Race these ghosts in a game patched with trials-frontier-patch (local services): in the patch repository's folder, with the game closed, add this bundle to your sources and update (later updates of the bundle arrive the same way):

```
python3 -I scripts/community.py add gtjeffw/trials-frontier-ghosts-jayuph
python3 -I scripts/community.py update
```

Everything is described in `trials-frontier-bundle.json`; the format is documented in the patch repository (`docs/BUNDLES.md`). `source` says where each entry came from: `save` (the game's save when exported: the years of online play, possibly also offline play since), `local-services` (played later in a patched game with local services), `downloaded-opponent` (another rider's ghost the game downloaded).

## Licence

The publisher releases this data under [CC0 1.0 Universal (public domain dedication)](https://creativecommons.org/publicdomain/zero/1.0/) (`CC0-1.0`). Trials Frontier itself belongs to Ubisoft/RedLynx; no game files are included.
