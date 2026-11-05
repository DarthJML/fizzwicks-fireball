# Fizzwick's Fireball

A small browser game: fling firebolts and fireballs, survive the waves, and grow your spell constellation between waves.

**Play:** https://darthjml.github.io/fizzwicks-fireball/

Controls (desktop): WASD or arrow keys move; mouse aims; hold left click to auto-fire Firebolt; right click or Space casts Fireball; Q casts Frost Nova and E casts Ward once unlocked; T opens the spell tree; 1/2/3 choose draft cards; M cycles sound modes (All → SFX only → Muted).

Controls (phone / X player card): Touch the left half and drag the floating joystick to move. Tap the right half to aim and fire a Firebolt, or hold and drag to auto-fire. Move and fire with two fingers. Use the big FIREBALL button, or tap/hold the smaller FIREBOLT button to target the nearest enemy. FROST NOVA and WARD stay visible but locked until drafted; active rings show cooldown. Tap ✦ at top-right for the spell tree, or the nearby sound button to cycle modes; tap a draft card to choose it.

It's one self-contained HTML file with no install, no audio requests and no tracking. Sound starts only after a tap, click or keypress; the 48-second original procedural score switches to a more intense boss arrangement, with a victory sting and short CC0 `game_sfx` one-shots layered with synthesis. Sound preference is stored locally. If WebAudio is unavailable, the game remains playable silently.

Fan parody, not affiliated with or endorsed by Mattel or the Barney franchise. Free, non-commercial.
