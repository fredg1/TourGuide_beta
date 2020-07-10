## TourGuide beta/WIP repository

A place where you can help beta-test (or get early access to) unofficially released changes.

Simply checkout the [appropriate branch](https://github.com/fredg1/TourGuide_beta/branches) in mafia's GCLI (master will only ever contain this README):

`svn checkout https://github.com/fredg1/TourGuide_beta/branches/ <branch_name> /`

Add comments, problems, recommendations and questions under [Issues](https://github.com/fredg1/TourGuide_beta/issues).


#### Additional info
Don't delete your original copy of TourGuide! Especially the file `relay_TourGuide.js`: I'm assuming you already have it since you most likely also have TourGuide, so I didn't duplicate it.

Be sure to clean your svn and relay folders when you're done testing/using a copy; they won't go by themselves...


Also, sadly, this obviously won't include any change you made to your own copy of Guide/TourGuide...

### Branches

[Pirate_route_rework](https://github.com/cdrock/TourGuide/pull/16): Full change/update/separation of the talisman o' namsilat and pirate-related "stuff". No testing done, so help is really appreciated on that one.

[sea-quest-tweaks](https://github.com/cdrock/TourGuide/pull/22): Changed the conditionals so that you won't simply get "Unless you discovered the currents already, in which case go to the corral." as often anymore. Also some comments were locked behind bad logic. Need to test if I didn't screw up anywhere.

[glitch-gilcht-tighcl](https://github.com/cdrock/TourGuide/pull/26): Added GSRN to free fights.

[vote-monster](https://github.com/cdrock/TourGuide/pull/25): add a reminder of how many more times the vote monster is a free fight.
