# cogito-tabulation
Cogito free tabulation prototype (no UI)

# Usage
I made this project independently solely because I didn't want to pay for Calicotab during the tournaments our club hosted. As someone that isn't a big fan of AI written code, I left it without a UI because it really isn't my area of expertise. I plan to add one when I learn how to.

# Guide
Read through `setupcheck.cpp` and fill in `conditions.txt` `debaters.txt` `rooms.txt` `teams.txt` accordingly based on the contestant information. Run it once at the beginning of the contest to make sure everything is working.
Read through `alloc.cpp` and fill in `responses.txt` based on the judge ballots. Run this after every round of the contest, and the team scores, speaker scores, and the draws will be updated accordingly in `teams.txt`, `debaters.txt`, and `rooms.txt`.

It will be nice to make backups of `teams.txt`, `debaters.txt`, and `rooms.txt` after each round by simply copying the file under a separate directory or a different name in case there is an issue with the program.

It's also a good idea to use google sheets or excel to store the teams, debaters, and rooms data because you can simply copy and paste the contents back and forth between the `.txt` format because of how tabbing works. Below is a google drive link to an example tournament:
- https://drive.google.com/drive/folders/1x7CCYPfJnYr93P9sUtIlrf1tkmn1jzhT?usp=drive_link
