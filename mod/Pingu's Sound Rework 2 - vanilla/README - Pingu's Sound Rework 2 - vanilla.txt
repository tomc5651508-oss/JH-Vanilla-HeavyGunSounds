Stand-alone sound rework for the stock game, IL-2 build 20261124. Replaces 'Pingu's Heavy Gun Sounds 2 - vanilla'
(disable that one). Not with Jungle Hawks or The 8th Airforce (their deltas carry the same rework).

25 Nov 2026 sound rework (built by scripts\jh_sounds_1124, base = stock MasterBank.bank of build 20261124,
sha1 49ddf746c4fcc76553e41c3f14eaa9786737c3df)
* Guns (all planes): VSM round of the same gun layered on every round, crack + suck-back pressure pulse, less bass than
  Heavy Gun Sounds 2, outside reverb with ground slap (inside the stock clip length), cockpit wing guns muffled,
  cockpit nose guns and gunner positions on cloned events with a mechanical breech clack (cfg SND_SHOOT Pos |z| < 0.6 m).
  Stock distance fall-off (Distance 0..3000 m automation, max 2800 m) kept.
* Bombs (main blast layer only, peak-aligned, 6-8 dB under stock), bullet/AP/HE metal hits, airframe over-g, radio
  noise, supercharger levers, ship horns, radial engine start-ups: VSM sample mixed into the stock samples (stock length).
* Radio beacons (VSM Morse_*, Lorenz_*, beaconcarrier, beaconstatic): flagged, NOT wired (no beacon event in the game).
Credit: sounds from VSM Sound Mod v7.5 (open source, used with credit) - see CREDITS - VSM sounds.txt.
Not heard in game. Offline renders only.
