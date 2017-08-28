# NPC

NPC Plugin ~ Originally by @onebone ~ Maintained by @LeverylTeam

### Features:
 - Tracks the player's movement
 - Commands can be set for NPCs
 - Messages can be set for NPCs
 - Uses the creator's skin as the NPC's Skin

### Commands:
 - /npc create <NPC NameTag>
   - Create an NPC
   - ```/npc create Im an NPC!```
 - /npc list
   - List all NPCs and their IDs
   - ```/npc list```
 - /npc remove <id>
   - Remove an NPC
   - ```/npc remove 3```
 - /npc message <message>
   - Set a message to an NPC (Messages sent to the player when Tapped)
   - ```/npc message Hi!```
 - /npc command <command without the slash>
   - Set a command to an NPC (Command executed when Tapped)
   - ```/npc command say Hellow World!```

### Configuration:
```yaml
save-on-change: true
include-on-player-list: true
max-distance-to-track-player: 8
```
 - save-on-change: Toggle to save the config on any NPC change
 - include-on-player-list: Toggle to include the NPCs on player list
 - max-distance-to-track-player: Max distance on how many blocks should the NPC track the player
