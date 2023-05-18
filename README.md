# Staff-management-plugin
A plugin for Minecraft developed in Java. 
This plugin allows you to authorize the staff of your server to be able to switch between "staff" mode and "player" mode 
so that they can also enjoy the server!

The plugin version is 1.0
Commands :

 - /onstaff Switches the player to "staff" mode and puts him in creative mode so that he can 
administer the server. Person cannot throw or put items in chests (editable).

 - /offstaff Switches the player to "player" mode and puts them on survival so they can play 
on the server. The person loses their administrator/moderator permissions.

Note: This plugin works with a permissions plugin (PermissionsEx) but this is editable.
For people to be able to do these commands, you need to give them the following permissions:
- onstaff.use
- offstaff.use
- 
For the plugin to know the original group of permissions of the player, it must be entered in the Main class.
