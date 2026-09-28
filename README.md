# RoomRadar — Smart-Search Floor Manager

A single-file web tool that helps students locate empty classrooms efficiently, using both traditional filters and AI text analysis.

## Features
- **Floor Grid** — live room availability organized floor-by-floor, computed from the 10 official odd-semester timetables (8 tracked rooms: IST 225, 227, 211 · 411, 416 · 518, 519 · 602)
- **AI Room Finder** — type naturally, e.g. *"I need an AC room on the ground floor for me and my team for the next 2 hours"*. The built-in parser extracts floor, duration, team size, amenities, day and time, then returns rooms free for the whole window — with honest handling when nothing matches
- **Traditional filters** — floor, capacity, AC, projector, day, time, and required free duration
- **Room details** — tap any room for its full day timeline and free windows

## Data
Room occupancy is derived from each section's printed *Venue* (home classroom). A room counts as occupied while its section has a class, and free during gaps, lunch, and periods timetabled elsewhere (labs, workshops, CDC/NSS/Yoga).

## Use
Open `index.html` in any browser — no backend, no build step. Hosted via GitHub Pages.
