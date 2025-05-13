# FFXI-HorizonXI-Maps
Some of the missing HD maps which I've taken time to edit myself.  These are based both on AkadenTK's Remapster Maps and Moop FFXI HD Hunting Maps for cleaner and more informative maps.

The map for Western Aletpa Desert is a modified version of Moops's map with the numbering re-edited to match those seen on the wiki maps.  I've also done a very minor fixes to the Yhoator Jungle and Palborough Mines 2nd floor maps where accessible routes were missing and also to the Yuhtunga Jungle map where branches leading back into Ifrit's Cauldron were incorrect and missing the location for the Cerment Headstone.

Currently I've only done a few 2048x2048 maps.  To use these create a new folder in Game/polplugins/DATS using whatever name you fancy and move the folders into that directory (minus the 2048x2048 folder.)  You'll need to ensure your launcher seetings are set to not overwrite the pivot.ini otherwise it will reset it each time to the default settings, and you'll need to edit the pivot.ini file found in HorizonXI/Game/config/pivot manually to place the custom maps above any other custom maps in the list like so:

	[overlays]
	0=horizonmusic
	1=xiview
	2=horizonoverrides
	3=gg101-maps
	4=moop-remapster-labeled
	5=remapster
	6=horizonhd

You can also use these maps with CatseyeXI although they are optimized more for HorizonXI so they'll be missing out extra and custom NMs and some custom book and homepoint locations may be slightly off.  Again you'll need to adjust the settings in the launcher to not overwrite the pivot.ini and and edit the pivot.ini file found in CatseyeXI/catseyexi-client/Ashita/config/pivot and set it up as so:

	[overlays]
	0=ffxi-lofi
	1=gg101-maps
	2=moop-remaster-labelled
	3=ffxi-hd
	4=catseyexi
	5=ffxi-maps\2048x2048

For more amazing remastered HD maps visit https://github.com/Moop-HorizonXI/FFXI-HD-hunting-maps

**NOTE:** Using Pivot allows you to add custom DAT files without writing over official files.  You can also disable custom DAT files without having to redownload all the official files should any of them be corrupted or not to your liking.  It's much preferred to install custom DAT files this way.

__New Maps__
|    <!-- -->          |        <!-- -->                     |
|----------------------|-------------------------------------|
| Cape Terrigan | Eastern Altepa Desert |
| Ro'Maeve | Ifrit's Cauldron |
| The Garden of Ru'hmet | Grand Palace of Hu'Xzoi |
| Pashhow Marshlands [S] | |

__Modified Maps__
|    <!-- -->          |        <!-- -->                     |
|----------------------|-------------------------------------|
| Yuhtunga Jungle | Yhoator Jungle |
| Western Altepa Desert | Palborough Mines Map 2 | 

Please also note that whilst the maps contain the remapster.com url at the bottom I am not part of the Remapster team.  If you have issues with the maps designed by Remapster then you'll need to contact their staff.

If you have any questions or suggestions about my maps please free to ping me on Discord @geekgirl101

![cape_terrigan](https://github.com/user-attachments/assets/3443727e-20cf-495f-9ef0-097f7ec24120)

![eastern_altepa_desert](https://github.com/user-attachments/assets/0b9276c3-da17-4eca-b042-a67f8f9fde34)

![ro_maeve](https://github.com/user-attachments/assets/f7a581dc-049b-4b7b-b9bc-a7be327d54a3)

![grand_palace_of_huxoi_2](https://github.com/user-attachments/assets/9560e2b1-2c5c-43d2-a6cb-ac95b0460bf9)
