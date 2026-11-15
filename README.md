# CapeSync

Mit **CapeSync** trägst du eigene Capes im **OptiFine-Format** (46x22, auch HD wie 92x44) oder im Vanilla-Format (64x32), ohne Account, ohne Webserver und ohne externe Dienste. Wähle dein Cape im Mod Menü aus. Andere Spieler, die die Mod ebenfalls haben, sehen es automatisch auf deinem Rücken (auch an den Elytra).

## Funktionen

- Capes im **OptiFine-Format** (46x22 / 92x44 …) und im Vanilla-Format (64x32)
- Auswahl direkt im **Mod Menü** (CapeSync → Konfigurieren), mit Seitenanzeige und Neu-laden-Button
- **Automatischer Sync auf Servern:** Beim Beitritt oder beim Wechseln sendet die Mod kurz eine Nachricht in den Chat. Mod-Nutzer blenden diese Nachricht aus und zeigen dein Cape an
- Sieht die Mod einen neuen Spieler mit der Mod, sendet sie dein Cape noch einmal, damit er es auch sieht
- Dein Cape wird sofort bei dir angezeigt, auch ohne Server und im Einzelspielermodus
- Rein clientseitig, kein Server-Mod nötig

## Eigene Capes hinzufügen

1. Lege PNG-Dateien in diesen Ordner:
   `.minecraft/config/capesync/capes/`
2. Öffne im Spiel das Mod Menü, wähle CapeSync und klicke auf *Neu laden*.
3. Klicke dein Cape an.

Du kannst Capes auch direkt in die Mod-Datei packen (Zip-Programm, Pfad `assets/capesync/capes/`).

Der **Dateiname ohne .png** ist der Cape-Name. Damit andere dein Cape sehen, brauchen sie dieselbe Datei mit demselben Namen. Teile also deine Cape-Dateien mit deinen Freunden.

## Anforderungen

- Minecraft **1.21.11**, Fabric Loader
- [Fabric API](https://modrinth.com/mod/fabric-api)
- [Mod Menu](https://modrinth.com/mod/modmenu) (für das Auswahlmenü)

## Hinweise

- Der Sync funktioniert nur zwischen Spielern, die CapeSync installiert haben und die Cape-Datei besitzen.
- Spieler ohne die Mod sehen die Nachricht `~cm:name` im Chat.
- Auf Servern, die den Chat umformatieren, kann es sein, dass Capes weit entfernter Spieler nicht erkannt werden.
- CapeSync ist nicht mit Mojang, Microsoft oder OptiFine verbunden. Es nutzt nur das bekannte Cape-Bildformat.
