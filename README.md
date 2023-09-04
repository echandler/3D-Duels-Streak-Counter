# 3D Duels Streak Counter

## How to install Chrome Extension (if it's not on Chrome webstore it won't update):
1. Download .zip file and extract somewhere.
2. Open Chrome extensions page.
3. Click developer mode in the upper right.
4. Drag the uncompressed folder into the window.
5. Click icon on task bar to open menu (man have to manually pin to taskbar to see it).

## How to install Tampermonkey script:
1. [Click here to install 3D streak counter for Geoguessr for Tampermonkey and Chrome](https://github.com/echandler/3D-Duels-Streak-Counter/raw/main/3dDuelsCounter.user.js).
2. [Click here to install Simple Reverse Geocoding Script (required)](https://github.com/echandler/Simple-Reverse-Geocoding-Script/raw/main/reverseGeocodingScript.user.js). [Link to Simple Reverse Geocoding Script repository](https://github.com/echandler/Simple-Reverse-Geocoding-Script).

## How to use:
1. To clear the settings press "!" (exclamation mark). If something happens with the counter, clearing the settings might fix it.
2. Press "CTRL" to make a squiggly line, with the mouse, around something you want to highlight.
3. Press "ESC" to access the menu (userscript only, with extension click icon on taskbar).
4. My currents "settings" in the menu:
   * State1 size: 20 (Score during game.)
   * State1 angle: 0.1 (Spotlight size, THREEJS calls it the spotlight angle.)
   * State2 size: 18 (Score between rounds.)
   * State2 angle: 0 (Turns off spotlight so it doesn't mix with Guess text. Guess spotlight, or angle, lights State2 if close enough.)
   * Guess size: 16
   * Guess angle: 1.26 (Wide angle, might fill whole screen.)
   * Guess text variables: $1 is your guess. $2 is the spawn. $3 is the previous score, used for incorrect answer.
