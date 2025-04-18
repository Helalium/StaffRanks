# Staffranks -- By Salzar

This mod adds ranks, in chat and in nametag.


## Base ranks

All ranks can be found in ranks.lua.

* Administrator
* Moderator
* Developer
* Builder
* Contributor
* VIP

## Commands

* `/add_rank <name> <rankname>` - Add a rank to player. If the rank name is 'clear', it resets the player's rank.
* `/ranks_list` - See the list of all ranks.
* `/view_rank <name>` - View a player's rank.

## Customization

If you want to modify existing ranks or create new ones, simply use the staffranks.register_rank() function and add the rank name, prefix and color.

## API

* `staffranks.register_rank(name, prefix, color)` - Registers a rank, with its name, prefix and color.
* `staffranks.rank_exist(rankname)` - Check that the rank exists.
* `staffranks.add_rank(name, rankname)` - Adds a specific rank to a player.
* `staffranks.set_nametag(player)` - Set a player's nametag.
* `staffranks.clear_nametag(player)` - Remove a player's nametag.
* `staffranks.rankslist()` - Displays the list of ranks.
* `staffranks.has_rank(player_name, rankname)` - Checks whether a player has a specific rank.
