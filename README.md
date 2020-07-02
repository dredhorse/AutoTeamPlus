# tShock AutoTeam

Code taken from https://github.com/Jewsus/AutoTeamPlus

tShock plugin that forces a user to be on a specific team.


## Installation

Copy the latest release from https://github.com/dredhorse/tShockAutoTeam/tree/master/release into your ServerPlugins folder

## Configuration

Give the users the specific permissions:

- autoteam.none   = no team
- autoteam.red    = red team
- autoteam.green  = green team
- autoteam.blue   = blue team
- autoteam.yellow = yellow team
- autoteam.pink   = pink team

via the group:

- group addperm groupname autoteam.red


Please note:

This doesn't work for groups which have the * permission or for members of the superadmin group.
