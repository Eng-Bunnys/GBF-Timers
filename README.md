![GBF Timers Logo](https://cdn.discordapp.com/attachments/1059460680920612924/1066506968430301234/Screenshot_2023-01-22_015445-removebg-preview.png)
# GBF Timers V2

### Warning 
V1 code is out-dated an no longer used, use only if you know what you're doing.

## Data Protection
### Due to this version being free for public use rather than closed access compared to V1, data protection is very important.

Your data will be closed and inaccessible by anyone, the data is updated using a computer and there is no manual work this means that no human will be in-between you and your data.
You can request data deletion and that process will also be automatically done using a computer to ensure no human can view your data.

Your data is encrpyted using AES256-CBC [256-bit Advanced Encryption Standard in Cipher Block Chaining mode], this protects your data by encrypting your data from the client to the secure database, TDE is also supported.

## How to access for free
[Click here](https://discord.com/api/oauth2/authorize?client_id=795361755223556116&permissions=1642787765494&scope=bot%20applications.commands) to invite GBF Timers to your server with the required permissions

## New Main Features

- Enhanced system performance and less loading times:
This was done by greatly improving the code and general connections to the server.

### New display features:
1. Semester naming to help identifiy which data is for which group
2. Just finished session difference from average session data

### Removed in-compatible features
1. System time welcome messages
2. System time footers

### Added Multi-User support
Now the system supports multiple users but users are limited to their own commands so no one can manipulate your data without access to your account.
This also means that now many users can use the timer and track their data for free.

### Level system

Since the system is now open to the public, we find that having a progression system helps keep people interested, we plan to improve this system in the future.
1. Sesaonal level
This is a temporary level that resets after each season/semester.
2. Account level
This is a permenant level.

### Small Updates
1. Added session topic
2. Added change session topic
3. Changed level up emoji
4. Renamed season to semester
5. Made leveling up easier for semester level and account level, 300 and 500 less respectively 
6. Added average time between breaks
7. Added semester recap in the reset command
8. Added the help command in the registry command as a tutorial
9. Removed rounding and added thousandth seperator and break number in the un-pause logic

### Bug Fixes
1. Fixed an issue where the pause command would run but never update the data to the DB.
2. Fixed a bug where when multiple initiate messages would be present, the old ones would update.
3. Fixed a bug that would display negative stats.
4. Fixed a bug that would give undefined for the total time
5. Fixed a bug that would close the timer without showing the session stats.
6. Fixed a bug where the buttons would close without reason.
7. Fixed a bug where when the user's internet is slow, the buttons would trigger but nothing would happen, this would cause the buttons to update but not the data.
8. Fixed a security issue where other users could tamper with your session.
9. Fixed a bug where the session would never end.
10. Fixed a bug where the pause timer would not stop.
11. Fixed a bug when the user would force stop while the timer would pause, this would cause the data to not update.
12. Fixed a bug in the time calculations.
13. Fixed a bug where the real and total time would be 1 second apart.
14. Fixed a bug where the display command would not run when in-sufficient data was provided.
15. Fixed a level system bug where it would take triple the hours required to level up
16. Fixed a bug where some stats would not reset when the reset command was ran.
17. Fixed a bug where the timer would kill the system when attempting to pause.
18. Fixed a bug where system would mix the button users with the original command author.
19. Fixed a bug where the system would give the wrong IDs.
20. Fixed a bug that would stop the session info from running.
21. Fixed a bug where the time would be negative if the break time was larger than the session duration
22. Fixed no embed colour for the timer info command
23. Fixed a bug that showed the s in units when the data was only 1
24. Fixed a bug that didn't reset the session topic even after the session ended
25. Fixed a bug that didn't reset the session topic in the reset command
26. Fixed a display bug that showed "second" instead of "seconds" when the time would be more than 1

GBF Timers is now available for public use and the source code is now open source.

### Future Plans

- Added a level leaderboard
- Cheater detection
- Custom embed colouring
- Streaks
- Semester score

## Under GBF
