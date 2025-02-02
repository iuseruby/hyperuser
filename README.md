pro commands for block game

# Connection
Type `node .` in terminal

- Type `/connect 0.0.0.0:3000` in Minecraft Bedrock chat panel
- Make sure to turn off General > "Require Encrypted Websocket" in the Settings
- When connected, a text "[hyperuser] Connection established" should appear

Have been tested on `1.21.x` ver

# Usage
`#` prefix is used to perform a hyper command

List of unique messages sent from user to execute something: (note that some aren't available on servers)

`#run <command>` - executes a command with respect to the user, can run hidden commands or even server commands like `/agent` entirely within Minecraft (refer to [the wiki](https://minecraft.fandom.com/wiki/Commands) for more information; obviously won't run admin commands when you're not an Operator)

`#delay <seconds/1000> <command>` - executes `#run <command>` after a delay

`#hotkey <key> <command>` - executes `#run <command>` when <key> is pressed, only available for Windows

`#addqueue <command>` - adds a command to the `queue` list, capped at 100

`#tellraw <string>` - displays <string> in the chat directly

`#queue` - batch executes the commands from `queue` all at once

`#deleteq` - deletes the `queue list`

`#pro` - enter pro mode

`#noob` - terminate websocket connection

# Features
- pro commands to elavate your gamer mode
