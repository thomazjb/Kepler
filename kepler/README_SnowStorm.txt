*----------------------*
*  Kepler v1.3         *
*  SnowStorm Guide     *
*                      *
*  By Quackster        *
*----------------------*

To get SnowStorm ready, please go to /tools/ and
copy the hh_gamesys_patch.cct into the folder where
your normal hh_gamesys.cct is. Do not replace any
hh_gamesys.cct files.

This should be your DCR folder.

Open up your external_variables.txt and find the highest
cast entry number to use, and then use the next one avaliable
for example, cast.entry.24=hh_tutorial exists, but there's no 25,
so we'll use 25.

cast.entry.25=hh_gamesys_patch

Add this line to the variables, so it should look somewhat like this:

cast.entry.22=hh_soundmachine
cast.entry.23=hh_poll
cast.entry.24=hh_tutorial
cast.entry.25=hh_gamesys_patch

Ensure there's no gaps in the cast entries, for example if
cast.entry.22 is missing, anything above that won't load.

Last of all, please run v1.3 migration SQL to 
enable SnowStorm to be playable on the server.

**IMPORTANT** Make sure that the tools/snowstorm_maps/ folder
stays intact as how it is when you downloaded Kepler v1.3.

This is important if you wish for SnowStorm maps to operate
correctly.