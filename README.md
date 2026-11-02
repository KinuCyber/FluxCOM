# FluxCOM

Minecraft-Fluxer bridge plugin.

## Repoistories

Canonical repository: https://git.sr.ht/~kinucyber/FluxCOM

Mirror repositories:
- GitHub: https://github.com/KinuCyber/FluxCOM
- Codeberg: https://codeberg.org/KinuCyber/FluxCOM

## Features

- **Bidirectional Chat Bridge**
Messages sent in-game appear in the Fluxer's `global` channel.
Messages sent in `global` channel appears in-game.

- **Fluxer Profiles**
Maintains a stateful database to store Fluxer user profile, allowing
the plugin to display it in-game.

- **Per-Player Toggle**
Each player can toggle off broadcast, being able to freely talk in
the server without disturing Fluxer users in `global` channel.

- **Event Broadcast**
Join, Quit, Death, etc events are broadcasted to `global` channel.

- **Live Log Streaming**
All server console logs are securely streamed to `console` channel.

- **Remote Console Execution**
Server administrators can type commands directly into the Fluxer
`console` channel, executing those commands as the server console.
