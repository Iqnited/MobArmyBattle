# Mob Army Battle
[Spiel-Idee von BastiGHG](https://www.youtube.com/watch?v=sfX7w9YCpUY)

_inspiriert von dem [Mod von Pious880](https://modrinth.com/datapack/mobarmy-battle), checkt ihn auch gerne ab_
## Das Spiel:
- Die Spieler teilen sich in 2 Teams auf
### Farm-Phase: 
  - Farmt als Team Mobs, die ihr in 3 Wellen nach Ablauf der Zeit gegen das gegnerische Team loslassen könnt
  - Farmt als Team Equipment, um die gegnerische Armee nach Ablauf der Zeit _möglichst schnell_ zu besiegen
### Konfigurations-Phase:
- Pro Welle habt ihr als Team 2 Minuten Zeit, um sie zusammenzustellen
- Eine Chest enthält alle Spawn-Eggs der Mobs, die ihr gekillt habt
- Die Mobs spawnen ohne KI, werden aber in der Kampf-Phase _aktiviert_
- Hinweise:
  - Mit Left-Klick können gespawnte Mobs wieder entfernt werden, um sie neu zu platzieren (30* / Team -> nur bedingt Min-Maxing des Equipments der Mobs möglich)
  - Mit Hilfe der temporären Blöcke können Mobs in der Luft platziert werden
  - Einige Mobs (Zombies, Skelette, Piglins etc.) können mit Right-Klick auf reitbare Mobs (Pferde, Hoglins et~~~~c.) als deren Reiter gespawnt werden
### Kampf-Phase:
- Ihr müsst als Team möglichst schnell die Wellen 1-3 des anderen Teams nacheinander besiegen
- Wenn alle Mobs der Welle gekillt wurden, startet automatisch die nächste Welle
- 2* / Team kann den noch vorhandenen Mobs Glowing gegeben werden (s. Commands)
- Wer stirbt, bekommt zunehmend höheren Respawn-Cooldown
- Wer als erstes Team alle Wellen besiegt hat, gewinnt!
## Player-Commands:
- _/battle team <Red | Green>_: Trete dem jeweiligen Team bei, alternativ über ein Item im Inventar möglich
- _/bp_: öffnet den Team-Backpack, alternativ über ein Item im Inventar möglich
- _/glow_: gibt allen noch vorhandenen Mobs Glowing für 5s, 2* / Team
## Admin-Commands:
- _/battle_
  - _start <minutes>_: startet die Farm-Phase des Battles
  - _time_
    - _add | remove <minutes>_: entfernt / addiert Zeit zur aktuellen Phase (auch bei Konfig-Phase nutzbar)
    - _skip_: Beendet die aktuelle Phase und startet die nächste
  - _randomizer <mode>_: aktiviert / deaktiviert einen Block-Randomizer
- _/skip_: während der Kampf-Phase: startet die nächste Welle für das Team des Spielers

##
**Auftretende Bugs bitte einfach reporten, dann schau ich, was sich da machen lässt ;D**

Ist btw meine erste Erfahrung mit java in Minecraft, also bitte nur konstruktives Feedback, danke!
