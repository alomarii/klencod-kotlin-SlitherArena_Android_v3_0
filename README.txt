Slither Arena v3.0 - Android Studio project
تصميم وبرمجة محمد العمري 730215825

1) Open Android Studio > File > Open > select this folder (SlitherArena).
2) Wait for Gradle sync (internet needed once).
3) Build > Build APK(s) -> app/build/outputs/apk/debug/app-debug.apk
   Or press Run with a phone connected (USB debugging).
Game file: app/src/main/assets/index.html
Network code: app/src/main/java/com/slither/arena/MainActivity.java

How to play two-player:
- Host phone: turn on Hotspot, open the game > "استضافة تحدي" > a 4-digit code appears.
- Other phone: connect to the host's Hotspot WiFi > "انضمام إلى تحدي" > type the 4 digits. Game starts automatically.

Game modes (host picks the mode, guest follows automatically):
- Classic / Shrinking circle / Pulsing circle / Open (huge, endless, respawn) / Timed 3 min / Fast
Magnet pickup: collect the magnet item to pull nearby loot for 10 seconds.

New in v3.0:
- FIX: eliminated snakes no longer respawn in any mode. Last snake alive wins (timed mode: highest score among survivors).
- Campaign: 10 levels with stars, unlocking, harder bots; free play with easy/normal/hard bots.
- Sudden death: after 2 minutes the arena starts shrinking so a round always ends.
- Minimap, kill counter + popups, sound effects, stats (wins / eliminations / best score), settings screen.
