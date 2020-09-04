## TourGuide beta/WIP repository

A place where you can help beta-test (or get early access to) unofficially released changes.

Simply checkout the [appropriate branch](https://github.com/fredg1/TourGuide_beta/branches) in mafia's GCLI (master will only ever contain this README):

`svn checkout https://github.com/fredg1/TourGuide_beta/branches/ <branch_name> /`

Add feedback (comments/problems/recommendations/questions) under [Issues](https://github.com/fredg1/TourGuide_beta/issues), or send a PM on Discord or KoL.
Sending feedback is encouraged.


#### Additional info
Don't delete your original copy of TourGuide! Especially the file `relay_TourGuide.js`: I'm assuming you already have it since you most likely also have TourGuide, so I didn't duplicate it.

Be sure to clean your svn and relay folders when you're done testing/using a copy; they won't go by themselves...


Also, sadly, this obviously won't include any change you made to your own copy of Guide/TourGuide...

### Branches

[low_key_summer_bugfix](https://github.com/cdrock/TourGuide/pull/39): Fixes the bug in which key tiles were reappearing once used on the door in LKS.

[shen](https://github.com/cdrock/TourGuide/pull/45): Pretty much a complete revamp of the quest. Now tell you where Shen will send you to in advance, and adds notifications in the respective quest tiles about that (like hole in the sky). Also, Copperhead Club informations (delay and behind the stache).

[snapper](https://github.com/cdrock/TourGuide/pull/48):
- Complete rework of the snapper tile. Now shows phylums based on your assumed needs, and shows the phylum tracked and in current location.  
- Adds a warning if you're bringing the snapper and its phylum tracking is undoing a banish.  
- Rework of the appearance_rates_adjusted function (used in the location bar and to calculate the average turns a task will take, like bounties), which now relies more confidently on mafia's data.  
- (Somewhat smaller) Rework of the location bar:  
  Having copies of a monster, form olfaction or olfaction-likes, stops monsters from being shown as simply "banished" (btw, plz report more locations in which banishes are impossible).  
  Also stops only displaying a "?" for meat and drop chance when underwater.  
  Also also, fixes what caused the partial blurring of the left side of the base drop % of monsters' items in the location bar popup.
