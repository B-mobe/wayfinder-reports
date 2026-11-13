# Wayfinder Data Reports

This repository collects data reports from players of the **Wayfinder** addon
(Classic Era, Season of Discovery and World of Warcraft: Forever).

Wayfinder can notice when something in the game doesn't match its own data -
a quest it doesn't know yet, a quest giver standing somewhere else, a reward
that changed, a dungeon entrance. With your permission it keeps a short list
of those differences, and you can send that list here so the next version of
Wayfinder is more accurate for everyone.

## How to send a report

1. In game, open Wayfinder's **Settings** and turn on
   **Help improve Wayfinder** (it is off by default).
2. Play as usual. Wayfinder only writes down differences from its own data.
3. Type `/wf report`, click **Select all** and copy the text (Ctrl+C).
4. Open a new issue here: **Issues > New issue > Data report**, paste the
   text into the box and submit.

Several players reporting the same thing confirms it - so even if you think
someone else has already sent it, your report still helps.

## What is in a report

Only game data:

- quest IDs, NPC IDs and where you met them (zone and map coordinates)
- quest rewards
- dungeon entrance positions
- the Wayfinder version, the game version (Era / Hardcore / SoD / Forever,
  with the client build number)
- your faction, race, class and level (the level at the moment each thing
  was noticed - quest availability depends on it)

No character names, realm names, chat, account details or anything else.
You can read the whole report before you paste it - it is plain text.

## What happens next

Reports are checked automatically against Wayfinder's data. Anything that is
already correct, or already reported, is closed with a thank-you. New
information is confirmed by reports from different players and then added to
a future Wayfinder update.
