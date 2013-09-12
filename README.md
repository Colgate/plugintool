plugintool
==========

Shell script to auto-update all current Bukkit plugins.


###Usage###
plugintool --auto : Automatically search and replace plugins based on release date VS last modify date of plugin
plugintool --full : Search and replace ALL plugins.
plugintool --help : Shows this help menu

###Installation###
Simply copy this script to somewhere you have access to. I keep mine in /usr/local/bin/

###Notes###
* This script requires your Bukkit Servers to be in a directory called /servers/ OR you to have basic shell scripting skills to change it. 
* This script is coded to use my Bukkit-CLI script, located at https://github.com/Colgate/MC-CLI . It only uses this for server restarts following the completion of the server updates.
