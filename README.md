# scoreboard

This repository is meant to be a simple solution for a simple problem. My family participates in gymnastics and ninja warrior programs at the local rec center. The gymnastics events had dedicated software that shows individuals' scores across all of the events, but the ninja program, which only has a timed obstacle course run as part of their skills demonstration, had nothing. This solution is a standalone html page with no extra dependencies, no libraries, no build steps, and no server required, capable of displaying a list of participants and sorting similar-digit times in a clean scoreboard.

Features:

- Auomatic sorting by time on data entry
- Brief highlighting when a cell is moved
- Multi-column layout to maximize the use of horizontal space
- Multiple groups
- Event data is saved to local storage until expressly cleared

Yes, if I really were making a solution that would rival actual dedicated programs for this purpose, I would include the ability to import, add, and remove entrants, save results, and other useful features that for now would add too much complexity or require the need of a server. This works for now, only requiring a quick manual edit of the various ninja warrior groups before an event.
