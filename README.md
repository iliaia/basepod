# basepod
A simple and grounded podcast rss creator from mp3 files
## The goal
1. Upload mp3 file with a podcast episode.
2. Rescan.
3. Do another things.
## Restrictions
1. No Database.
2. No web server (static only).
3. Manual file manipulations.
4. Only one podcast (for now).
## Technical solution
1. Episode data is inside mp3 file, rescan on each rescan.
2. Podcast data is inside yaml file, rescan on each rescan.
