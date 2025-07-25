# FFXI-HD-Maps
Some of the missing HD maps which I've taken time to edit myself.  These are based both on [AkadenTK's Remapster Maps](https://github.com/AkadenTK/remapster_maps) and [Moop FFXI HD Hunting Maps](https://github.com/Moop-HorizonXI/FFXI-HD-hunting-maps) for more higher definition maps.

For player preference there are 2 types of maps you can choose from.  Hunting Maps are maps that I've both created myself and edited to include more data such as chest locations, quest markers, gathering points, and monster spawn areas similar to Moop FFXI HD Hunting Maps.  Clean Maps are unadulterated versions of the maps I've created myself or fixed that doesn't include all the extra data for more cleaner looking maps similar to AkadenTK's Remapster Maps and are suitable for players who want the legacy look but without all the clutter.

To use these create a new folder in Game/polplugins/DATS using whatever name you fancy and move the ROM folder and all of its content into that directory.  You'll need to ensure your launcher seetings are set to not overwrite the pivot.ini otherwise it will reset it each time to the default settings, and you'll need to edit the pivot.ini file found in HorizonXI/Game/config/pivot manually to place the custom maps above any other custom maps in the list like so:

	[overlays]
	0=horizonmusic
	1=xiview
	2=horizonoverrides
	3=gg101-maps
	4=moop-remapster-labeled
	5=remapster
	6=horizonhd

You can also use these maps with CatseyeXI although they are optimized more for HorizonXI so they'll be missing out extra and custom NMs and some custom book and homepoint locations may be slightly off.  Again you'll need to adjust the settings in the launcher to not overwrite the pivot.ini and edit the pivot.ini file found in CatseyeXI/catseyexi-client/Ashita/config/pivot and set it up as so:

	[overlays]
	0=ffxi-lofi
	1=gg101-maps
	2=moop-remapster-labeled
	3=ffxi-hd
	4=catseyexi
	5=ffxi-maps\2048x2048

**NOTE:** Using Pivot allows you to add and remove custom DAT files which override the official files.  It's much preferred to install custom DAT files this way so you don't accidentally break your game by overwriting the official files and need to redownload all the official files again.

__New Maps__
|    <!-- -->          |        <!-- -->                     |
|----------------------|-------------------------------------|
| Cape Terrigan | Eastern Altepa Desert |
| Ro'Maeve | Ifrit's Cauldron |
| The Garden of Ru'hmet | Grand Palace of Hu'Xzoi |
| Pashhow Marshlands [S] | Ordelles Caves |
| West Sarutabaruta [S] | North Gustaberg [S] |
| Jugner Forest [S] | Meriphataud Mountains [S] |
| Sauromugue Champaign [S] | |

__Modified/Fixed Maps__
|    <!-- -->          |        <!-- -->                     |
|----------------------|-------------------------------------|
| Yuhtunga Jungle | Yhoator Jungle |
| Western Altepa Desert | Palborough Mines Map 2 | 
| Uleguerand Range | Temple of Uggalepih |
| Davoi | The Eldieme Necropolis |
| Bostaunieux Oubliette Map 2 | Bostaunieux Oubliette Map 3 |
| Beadeaux | Maze of Shakrami |
| Xarcabard | Jugner Forest |
| Pashhow Marwshlands | Castle Oztroja Maps 2, 5, 6 and 7 |

Please also note that whilst the maps contain the remapster.com url at the bottom I am not part of the Remapster team.  If you have issues with the maps designed by Remapster then you'll need to contact their staff.

If you have any questions or suggestions about my maps please free to ping me on Discord @geekgirl101, or you could try to contact me on CatseyeXI @Melanie

A big thank you to AkadenTK and his crew and to Moop for their years of hard work into creating HD maps for Final Fantasy XI.

| Hunting | Clean |
|-----------------------------|------------------------------|
| ![cape_terrigan](https://github.com/user-attachments/assets/f7337b23-76bf-4827-b4ca-affc1a21b509) | ![cape_terrigan](https://github.com/user-attachments/assets/9ef06432-136c-4e2f-b277-873c9241e4d6) |
| ![eastern_altepa_desert](https://github.com/user-attachments/assets/ff0c1800-d45c-409e-833f-8ee297324edb) | ![eastern_altepa_desert](https://github.com/user-attachments/assets/1c39488f-e967-40a8-8782-78bc8ee2a0ea) |
| ![ro_maeve](https://github.com/user-attachments/assets/78454de6-ce65-4352-927d-b3bc72ddb115) | ![ro_maeve](https://github.com/user-attachments/assets/2f89fcd7-7962-4b6a-85b5-b8b9b01aab7c) |
| ![grand_palace_of_huxoi_2](https://github.com/user-attachments/assets/8ab0298e-4502-4231-bdf6-23817f06b755) | ![grand_palace_of_huxoi_2](https://github.com/user-attachments/assets/dacfae8d-d27c-47ef-a3c0-c90123b60663) |
