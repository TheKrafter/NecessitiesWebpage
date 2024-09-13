---
layout: home
title: Necessities
subtitle: ROADMAP
---

# Project Roadmap

## Permissions

- [ ] By module (nc.module.command)
- [ ] Sane default groups (nc.player, nc.mod, nc.admin)
- [ ] None applied by default

## Modules

- [ ] Teleportation:
  - [ ] Utility to check for safe locations to teleport to
  - [ ] Random teleportation (rtp)
  - [ ] tp: normal teleport command (to player, or coords) [staff]
    - [ ] tpall: teleport all players in server [staff]
    - [ ] tphere
    - [ ] Option for staff to override /tptoggle
    - [ ] tpauto: auto accept requests
    - [ ] tpoffline: tp to player's last known logout location
  - [ ] tpa/tpask: request to teleport to another player
    - [ ] tpahere
    - [ ] tpacancel
    - [ ] tpdeny
    - [ ] tpaccept
    - [ ] tpaall: request to teleport all players here [staff]
  - [ ] back: tp to prev. location
  - [ ] home: homes system
  - [ ] spawn: teleport to spawn point
  - [ ] Warps system
    - [ ] set/del/info/tp

- [ ] Punishment
  - [ ] Jails?
  - [ ] Mute
  - [ ] Kick
  - [ ] Kickall
  - [ ] Ignore
  - [ ] Ban
  - [ ] BanIP
  - [ ] SocialSpy
  - [ ] TempBan
  - [ ] TempBanIP
  - [ ] UnBan/Pardon

- [ ] Tools
  - [ ] /break: breaks the block you are looking at
  - [ ] /vanish, /v
  - [ ] /invsee
  - [ ] /clearinventory, /clear, /clean, /clearinv
  - [ ] /clearinventoryconfirmtoggle
  - [ ] /suicide
  - [ ] /gamemode
  - [ ] /remove, /butcher, /killall, /mobkill: kills all of specific entity in world

- [ ] Building
  - [ ] /more: top up stack in hand (to specified or 64)
  - [ ] /bigtree: spawn a big tree
  - [ ] /tree: spawn a normal tree
  - [ ] /give
  - [ ] /unlimited: allow unlimited placing of items
  - [ ] /item, /i: get an item
  - [ ] /spawner: change mob of spawner
  - [ ] /top: tp to the highest block above you
  - [ ] /jump: jump to nearest block in line of sight

- [ ] Effects
  - [ ] /lightning, /smite, /shock: strike player with lightning
  - [ ] /ice: freezes a player in powdered snow ice effect
  - [ ] /speed: change fly or walk speed
  - [ ] /rest: rests you or specified player
  - [ ] /ext, /extinguish: extinguishes player
  - [ ] /burn
  - [ ] /feed, /eat: satisfy hunger (and saturation)
  - [ ] /heal

- [ ] Admin
  - [ ] /powertool: assign command to item when used
  - [ ] /spawnmob
  - [ ] /sudo: execute as player
  - [ ] /god
  - [ ] /customtext: register custom text commands
  - [ ] /exp, /xp
  - [ ] /enchant
  - [ ] /gc, /mem, /lag, /tps, etc.: reports memory, uptime, and tick info
  - [ ] /thunder: enable/disable thunder
  - [ ] /time: display/change world time
  - [ ] /setspawn
  - [ ] /weather
  - [ ] /firework: modify a stack of fireworks

- [ ] Utility
  - [ ] /disposal
  - [ ] /condense
  - [ ] /book (reopening and editing signed books)
  - [ ] /hat: set current item as hat
  - [ ] tool benches:
    - [ ] /workbench
    - [ ] /cartographytable
    - [ ] /grindstone
    - [ ] /anvil [perms]
    - [ ] /loom
    - [ ] /smithingtable
    - [ ] /stonecutter
  - [ ] /seen: shows last logout time of player
  - [ ] /skull
  - [ ] /itemname, /name, /iname
  - [ ] /itemlore, /lore, /ilore

- [ ] Info
  - [ ] /info
  - [ ] /rules
  - [ ] /recipe: how to craft items
  - [ ] /compass
  - [ ] /motd
  - [ ] /ping
  - [ ] /playtime
  - [ ] /whois (player info)
  - [ ] /realname
  - [ ] /list
  - [ ] /near: lists nearby players
  - [ ] /getpos, /depth: get pos of self [mods: of others]

- [ ] Chat
  - [ ] /mail system
  - [ ] nicknames
  - [ ] /msg, /w, /pm, /tell
  - [ ] /me
  - [ ] /broadcastworld
  - [ ] /broadcast
  - [ ] /helpop: msg online staff
  - [ ] /nick
  - [ ] /r, /reply
  - [ ] /afk: marks you as afk

- [ ] Economy
  - [ ] Essentials-style worth.yml 
  - [ ] /setworth
  - [ ] /worth: calculate item worth (of hand or specified)
  - [ ] /payconfirmtoggle: whether you are prompted to confirm payments
  - [ ] /balancetop, /baltop
  - [ ] /balance, /bal
  - [ ] /eco, /economy: manages economy [admin]
  - [ ] /pay
  - [ ] /sell

- [ ] Kits
  - [ ] /createkit
  - [ ] /kitreset, /kitreset
  - [ ] /kit, /kits
  - [ ] /showkit
  - [ ] /delkit

## What won't be implemented

- [ ] Overcomplicated "gag" commands such as /beezooka, /kittycannon, /nuke, /fireball, and /antioch
- [ ] Commands that mess up players' synchronization with the server, like /ptime and /pweather
- [ ] Server management features such as /backup and essentialsx's restart script: that should be handled by your server management panel.