# xonotic-rate-maps
A hacky way to go through a bunch of maps and "rate" them

Clone this repository in your ~/.xonotic directory (so that it's a sibling to the data directory)

This will make some changes to your resolution, so you might want to use a different userdir (say ~/.xonotic1) and clone this repository there and append this flag: `-userdir ~/.xonotic1`

Put the maps your want to rate inside of this folder (xonotic-rate-maps) and run `./create-maplist.sh` -- this will generate a campaignratemaps.txt file.

Start the game with the flags `-game xonotic-rate-maps +exec rate_maps.cfg`

e.g. `./all run -game xonotic-rate-maps +exec rate_maps.cfg`

Start campaign.

*binds are*:
* 1 good
* 2 bad
* 3 kansas
* 4 incomplete
* 5 needs love
* j kill yourself (killing yourself wins the match)
