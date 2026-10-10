# The Night Desk

A browser-based investigation game. You are a night-shift records operator at the Special Intelligence Network (SIN) in 2011. Field agents call in, you search the databases, and the people the system calls "unremarkable" turn out to be the ones who vanish.

Everything is original: story, characters, world and scripts.

## Play

Open `night-desk.html` in any modern browser. It is a single file with no build step and no dependencies.

For testing, open `The Night Desk-test.html`. It adds a top bar with buttons 1 to 17 to jump to any mission. Remove it for release.

## How it plays

- Answer incoming calls and read what the agent needs.
- Click the objective at the top, then click the matching data on screen. A line connects them, and the answer lands in your reply options to send.
- Tools unlock as the story goes on: HumanDB, VesselDB, CarDB, BankDB, KinTree, GeoMap, NewsDesk, Lamplighter (the SIN AI) and AudioLab.
- Files and folders you receive stay on the desktop.
- Progress saves in your browser (localStorage). Use **Continue** on the start screen to resume.

## Status

- 17 missions in five acts, 74 objectives, ending on a report, bury or leak choice.
- Modern dark navy terminal UI.
- No sound yet.
- Missions 1 to 6 reuse early case shells and may be rewritten.

## Project notes

- Stack: plain HTML, CSS and vanilla JavaScript, with async mission scripts.
- Mission engine primitives: `say`, `ask`, `reply`, `objective`, `ring`, `join`, `desk` (desktop folders) and `reset`.
- Story and world details live in the World Bible document, not in this repo.

## Credits

Story and design: Tadashi
