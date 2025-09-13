# teleport

Move your character to everywhere in same zone.

## Commands

Toolbox(/8) | Description
--- | ---
**tp loc** | Show coordinates zone id and x, y, z, w.
**tp drop [x]** | Drop your HP to `x` percent for slaying.
**tp save [name]** | Save your location name.
**tp to [name]** | Teleport to your saved location `name` (if not have name will open GUI for your bookmark).
**tp remove [name]** | Remove your saved location `name`.
**tp blink [distance] [z]** | Blink to forward with `distance` and `z` (can ignore z if you are sure not underground).
**tp back** | Move back to your last location before teleport.
**tp [up/down] [z]** | Teleport to up or down by `z`.
**tp [x/y/z] [+/-] [distance]** | Teleport follow side +/- with `distance`.
**tp [x] [y] [z]** | Teleport with manually coordinates.
| Command | Parameter | Description | Example |
| ----------------------- | ------ | ----------------------- | --------------------- |
| `/ga` | *(none)* | Toggle the module on/off and refresh/remove markers | `/ga` |
| `/ga ui` | *(none)* | Open the graphical settings interface (GUI mode only) | `/ga ui` |
| `/ga visit start` | *(none)* | Start auto-visiting resource points (teleports and gathers in list order) | `/ga visit start` |
| `/ga visit stop` | *(none)* | Stop visiting | `/ga visit stop` |
| `/ga visit clear` | *(none)* | Clear the pending visit list | `/ga visit clear` |
| `/ga visit list` | *(none)* | List the pending coordinates (shows up to the first 10) | `/ga visit list` |
| `/ga visit dwell <seconds>` | `<seconds>` | Set dwell time per point in seconds (minimum 1s) | `/ga visit dwell 15` |
| `/ga visit dwell` | *(none)* | Show the current dwell time setting | `/ga visit dwell` |
| `/ga visit addhere` | *(none)* | Add your current location to the pending list | `/ga visit addhere` |
| `/ga visit` | *(none)* | Show usage for `visit` subcommands | `/ga visit` |
