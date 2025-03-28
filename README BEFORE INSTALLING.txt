#######################################################################
#-----KBNHUD v517 - Stoyat Devchonki Edition - README-----#############
#######################################################################

#################################################################################
#-----Here's to decades gone past and decades to come. Take care, everyone!-----#
#################################################################################

# Hello, and again welcome to the instructional readme file.

Steam Group, join for updates: http://steamcommunity.com/groups/KBNHud
Screenshots album (imgur): https://imgur.com/a/2DSMJ6X
KBNHUD GitHub: https://github.com/Jotunn/KBNHud
KBNHud GitHub Wiki, this has detailed instructions and help: https://github.com/Jotunn/KBNHud/wiki
My Discord: https://Discord.gg/NhnSysw
HUDS.TF Discord: https://discord.gg/Y5vUPyyGVP

######################################################
########-------------------------------------#########
########------------INSTRUCTIONS:------------#########
########-------------------------------------#########
######################################################

####################################################################################################
#-------FOR DETAILED HELP, GO TO THE GITHUB WIKI HERE: https://github.com/Jotunn/kbnhud/wiki-------#
####################################################################################################

#################################
#-------OS Compatibility:-------#
#################################

KBNHud is compatible with every OS that TF2 runs on, these being:

Windows
Mac OS
Linux (KBNHud is developed in Linux)

###############################
#-------How to Install:-------#
###############################

Extract kbnhud v[version #].zip, which should create a folder of the same name.

############
#-WINDOWS:-#
############
Copy+Paste the kbnhud v[version #] folder into: 

"Program Files(x86)/Steam/steamapps/common/Team Fortress 2/tf/custom"

Or if you have TF2 installed on a secondary drive

"(Letter of your games drive)/SteamLibrary/SteamApps/common/Team Fortress 2/tf/custom"

###########
#-MAC OS:-#
###########
Copy+Paste the kbnhud v[version #] folder into:

"(home folder)/Library/Application Support/Steam/SteamApps/common/Team Fortress 2/tf/custom"

Or to:

"(Games drive)/SteamLibrary/SteamApps/common/Team Fortress 2/tf/custom"

#########################
#-LINUX (Most distros):-#
#########################
Copy+Paste the kbnhud v[version #] folder into: 

"~/.steam/steam/steamapps/common/Team Fortress 2/tf/custom"

Or to:

`(Games drive)/SteamLibrary/steamapps/common/Team Fortress 2/tf/custom`

#If the above isn't exact to your distro, simply use the manage files menu option from within steam. The above example is the file path for most distros, as steam makes a folder link to the local data folder used by the distro within /.steam/#

Please also note the fonts get weird depending on the desktop environment that is first installed with your distro. As Microsoft iterates on WSL, more and more Windows functions are cropping up. 
KBNHud is configured to work best with Ubuntu and Arch running at 1080p and all of the flaws it has; the two DEs (desktop environments) that I have tested to work near flawlessly with minor changes are KDE Plasma and XFCE.
The HUD should work out of the box on XFCE4 and KDE Plasma wihtout any further modification, at least in my own testing
Most others will never quite render fonts properly. I would recommend not using default Ubuntu anyway, as KDE Plasma far outclasses the Gnome based Unity DE that Ubuntu uses. Kubuntu (Ubuntu with KDE) or Xubuntu (Ubuntu with XFCE) are my recommendations. 
KDE is the better one for beginners, XFCE is faster and lighter, but for more advanced users.

THE FINAL FILE SETUP SHOULD LOOK LIKE THIS:

tf
└── custom
    └── kbnhud_v[version #]
        ├── ^customizations
        ├── cfg
        ├── materials
        ├── resource
        ├── scripts
        ├── sound
        ├── info.vdf
        ├── README BEFORE INSTALLING.txt
        ├── Screenshot Album.html
        └── v[version #] CHANGELOG.txt

#########################
#---HELP AND SUPPORT:---#
#########################

This HUD may not work with certain localizations of TF2, because of the custom fonts used in the HUD.

The following can help resolve issues:

-use the command “hud_reloadscheme” in the console
-restart TF2 / Steam
-verify TF2’s game cache on steam
-re-download & re-install the hud
-uninstall and reinstall TF2, then reinstall the HUD

You can submit bug reports & questions via the GitHub issue tracker.
You may also Submit a pull request on GitHub, and that is great for me since you can make your own fixes and I can simply merge them into the master branch, and copy them into the versions stored on my computer.
This or simply sending me a ping over on steam or Discord are the best ways to let me know something is borked. Links to the steam group, my Discord, and the HUDS.TF Discord are at the top of the readme.

################
#---Credits:---#
################

HUD BASE: KNHUD, which was based on m0rehud

CROSSHAIRS: Broesel, Knuckles, Seeker, m0re, Fog, ToonHud, Garm3n

STREAMER MODE: Whisker/budhud

KN-EDIT MODE: Old KNHUD mods, name from Hypnotize

MENU VTFS: extracrispy & Rawsor

MAIN MENU BACKGROUND, BANNERS: Alena Aenami, via her ArtStation. The piece used is called Stardust.

HITMARKERS: Originally written by Quartz, updated versions by Hypnotize

CLOSED CAPTIONS: Clovervidia


#######################
#---Special Thanks:---#
#######################

Thanks to: Chippy, Quartz, Garm3n, Sinders, rays, OMP, Hypnotize, and the HUDS.TF Discord for many many HUD elements and developement help.

Thanks to Clovervidia for the new captions.

Further thanks to Joe Prince for the creation of Maven Pro, the core font of this HUD, and making the font available to all for free. If you want the font for yourself, the files for all of the types are in the HUD fonts folder, alternatively, you can download the font at the link below.
https://fonts.google.com/specimen/Maven+Pro

And a big thanks to everyone else not mentioned here who lent a hand or maybe some code over these 10 long years, whether you're still around in this or not. It's been an honor and a pleasure, and I wish all of you the best on your continuing paths; while I walk mine. Let's see if TF2 lives for another 10 years.
