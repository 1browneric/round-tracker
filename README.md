# Round Tracker

Eric's solo tournament round tracker — one self-contained HTML page per round.
Stats entry (shots, putts, FIR/GIR, penalties) mirrored to the Golf Rounds 2026
sheet schema, plus the per-hole course book (hole diagram, interactive green
map with pin + suggested target, pin sheet). State syncs across devices over a
private ntfy.sh channel; Save round publishes the round JSON for Home Base
ingestion ("pull my round").

Convention: root index.html = the current round's course. Past rounds move to
rounds/<slug>.html before a new one lands.

Built from the home-base round-tracker skill; sibling of
https://github.com/1browneric/sunday-game.
