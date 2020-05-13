# Chantier de traduction fr ModPack Omega

## TODO

* trad du dossier **A_Traduire**
* chk eng --> fr, voir si il n'y a pas encors des mod sans `_l_french`
* test ingame voir si le reorga crash
* Listes des mod du pack ici et checklist pour les id's
* add - `/localisation-synced` et des sub de `/common` pour la trad.

### Pour rappel

### Creating Localisation Files

>In the root mod folder (not in common), create a folder named "localisation" spelled with an s. Note, some other paradox titles may use the Americanized "localization" with a z.
Optionally, create language subfolders within the "localisation" folder. This is organizationally helpful but not required.
Stellaris's localisation files are encoded as UTF-8-BOM. They must be encoded in UTF-8-BOM, as even UTF-8 will fail to be parsed by Stellaris, and will not work.
>The easiest way to get the correct encoding is to copy an existing Stellaris .yml file and modify it.
Alternatively, simply create a standard text file and save it as .yml with UTF-8 with BOM encoding. Various text editors, such as Notepad++ and Visual Studio Code, will allow you to manually save with encoding UTF-8 with BOM
>>The file name must end in "_l_language", otherwise it will not be read.
The first line of any localisation file must be l_language:, otherwise it will not be read.
Example file name: mod_buildings_l_english.yml
>Naming a YML file the same as a vanilla YML file will overwrite vanilla. Doing this is not recommended, unless you are trying to change (almost) all of the entries in the file. Localisation entries can be overwritten individually, by saving them in the "Replace" folder. See overwrite section.

### File Encoding

>Open the YML file using a text editor. Editors such as Notepad++ and Visual Studio Code are recommended, however, if those aren't .available, even standard Notepad will work.
Convert the file to UTF-8 with BOM
If using Notepad++, go to menu bar, open the Encoding menu.
If using VSC, go to the bottom right corner and click on the encoding (UTF-8 by default), then click Save with Encoding. Alternatively, it is possible to modify the settings so YML files created using VSC have UTF-8 with BOM encoding by default.
If using Notepad, go to Save As..., then change the encoding and save the file.
If the options listed are UTF-8 and UTF-8 with BOM (or similar), use UTF-8 with BOM.
If the options listed are UTF-8 without BOM and UTF-8 (or similar), use UTF-8.

### Overwriting Vanilla Text

>To overwrite vanilla localisation keys (or keys from other mods), create a folder named "replace" inside your "localisation" folder. Localisation files in this folder will load after all other localisation files, and overwrite any duplicate keys. In this way it is not necessary to overwrite entire localisation files, as individual key entries will be overwritten by the last loaded file, LIOS (Last in, only served). It is possible to overwrite localisation without a "replace" folder, however this is not a reliable method.

## Liste des modes

1 - Machine Shipset ; https://steamcommunity.com/sharedfiles/filedetails/?id=2077186491 (Habitat cassé, en attente de maj paradox pour maj du mod)

2 - United Fleet ; https://steamcommunity.com/sharedfiles/filedetails/?id=2027015321 (patch 2.7.1)

3 - (-NSC2 Season 5-) ; https://steamcommunity.com/sharedfiles/filedetails/?id=683230077 (patch 2.6* éventuelle maj à voir)

4 - Infestation - A Hive Mind Origin ; https://steamcommunity.com/sharedfiles/filedetails/?id=2087384056 (patch 2.7.1)

5 - 36 Building Slots ; https://steamcommunity.com/sharedfiles/filedetails/?id=1630649870 (patch 2.7.1)

6 - APSR: Anomalies, Planetary and Space Resources ; https://steamcommunity.com/sharedfiles/filedetails/?id=1346877266 (En attente de maj suite à altération des districts de la 2.7) [Maj majeure 3.0 en préparation, sortie inconnue]

7 - Extra Ship Components 3.0 [2.4+] ; https://steamcommunity.com/sharedfiles/filedetails/?id=1885775216 (patch 2.7.1)

8 - Gigastructural Engineering & More (2.7) ; https://steamcommunity.com/sharedfiles/filedetails/?id=1121692237 (patch 2.7.1)

9 - Planetary Diversity - Unique Worlds ; https://steamcommunity.com/sharedfiles/filedetails/?id=1740165239 (patch 2.7.1)

10 - The Zenith of Fallen Empires 3.0 ; https://steamcommunity.com/sharedfiles/filedetails/?id=2044599287 (patch 2.7.1)

11 - The Zenith of Fallen Empires: Ambitions of Power ; https://steamcommunity.com/sharedfiles/filedetails/?id=2053987275 (patch 2.7.1)

12 - The Zenith of Fallen Empires: Automated Industries ; https://steamcommunity.com/sharedfiles/filedetails/?id=2062797756 (patch 2.7.1)

13 - The Zenith of Fallen Empires: Secrets of the Fallen Empires ; https://steamcommunity.com/sharedfiles/filedetails/?id=2087871245 (patch 2.7.1)

14 - The Zenith of Fallen Empires: Societal Ascendance ; https://steamcommunity.com/sharedfiles/filedetails/?id=2071119457 (patch 2.7.1)

15 - Ancient Cache of Technologies ; https://steamcommunity.com/sharedfiles/filedetails/?id=1419304439 (patch 2.6* éventuelle maj à voir)

16 - Ancient Cache of Technologies: Override ; https://steamcommunity.com/sharedfiles/filedetails/?id=1504307690 (patch 2.7.1)

17 - Archaeology Story Pack ; https://steamcommunity.com/sharedfiles/filedetails/?id=1993869579 (patch 2.7.1)

18 - Bigger Planet View ; https://steamcommunity.com/sharedfiles/filedetails/?id=1587178040 (patch 2.7.1)

19 - Event Horizon Offset Facility ; https://steamcommunity.com/sharedfiles/filedetails/?id=2008059495 (patch 2.7.1)

20 - Expanded Colours [180 Colours] ; https://steamcommunity.com/sharedfiles/filedetails/?id=682090850 (patch 2.7.1)

21 - Extra Fallen Empires ; https://steamcommunity.com/sharedfiles/filedetails/?id=1812858232 (patch 2.7.1)

22 - Guilli's Planet Modifiers 2.6 ; https://steamcommunity.com/sharedfiles/filedetails/?id=865040033 (patch 2.6* éventuelle maj à voir)

23 - Masters of Nature ; https://steamcommunity.com/sharedfiles/filedetails/?id=1649338884 (patch 2.5* éventuelle maj à voir)

24 - More Origins Mod ; https://steamcommunity.com/sharedfiles/filedetails/?id=2025131190 (patch 2.7.1)

25 - Multiple Crises ; https://steamcommunity.com/sharedfiles/filedetails/?id=686276531 (patch 2.7.1)

26 - Scoot's Relic Wars ; https://steamcommunity.com/sharedfiles/filedetails/?id=1937783525 (patch 2.3* éventuelle maj peu probable)

27 - Planetary Diversity ; https://steamcommunity.com/sharedfiles/filedetails/?id=819148835 (patch 2.7.1)

28 - Planetary Diversity - Exotic Worlds ; https://steamcommunity.com/sharedfiles/filedetails/?id=1732437279 (patch 2.7.1)

29 - Planetary Diversity - More Arcologies ; https://steamcommunity.com/sharedfiles/filedetails/?id=1732447147 (patch 2.7.1)

30 - Planetary Diversity - Planetary Habitats ; https://steamcommunity.com/sharedfiles/filedetails/?id=1878751971 (patch 2.7.1)

31 - Planetary Diversity - Shroud Worlds ; https://steamcommunity.com/sharedfiles/filedetails/?id=1960179456 (patch 2.7.1)

32 - Plentiful Traditions 2.6.2 ; https://steamcommunity.com/sharedfiles/filedetails/?id=1311725711 (patch 2.6.2* éventuelle maj à voir)

33 - Plentiful Traditions 2.6.2 - Extra Perks ; https://steamcommunity.com/sharedfiles/filedetails/?id=1333526620 (patch 2.6.2* éventuelle maj à voir)

34 - Precursor Story Pack ; https://steamcommunity.com/sharedfiles/filedetails/?id=1999328266 (patch 2.7.1)

35 - Starbase Buildings & Modules ; https://steamcommunity.com/sharedfiles/filedetails/?id=1834615504 (patch 2.4* éventuelle maj peu probable)

36 - More Events Mod ; https://steamcommunity.com/sharedfiles/filedetails/?id=727000451 (patch 2.7.1)

37 - Storypack: The Nyblax and the Collector ; https://steamcommunity.com/sharedfiles/filedetails/?id=1878601358 (patch 2.7.1)

38 - Titan Interdictor Module ; https://steamcommunity.com/sharedfiles/filedetails/?id=1997761958 (patch 2.5* éventuelle maj à voir)

39 - Unofficial Hive DLC: Forgotten Queens ; https://steamcommunity.com/sharedfiles/filedetails/?id=1715190550 (patch 2.7.1)

40 - Unofficial Machine & Synthetic Empire DLC ; https://steamcommunity.com/sharedfiles/filedetails/?id=1762062219 (patch 2.7.1)

41 - !!!!Machine DLC & Hive DLC Patch ; https://steamcommunity.com/sharedfiles/filedetails/?id=1800648231 (patch 2.7.1)

42 - Yukari voice ; https://steamcommunity.com/sharedfiles/filedetails/?id=825050563 (patch 2.6* éventuelle maj à voir)

43 - Ziaskehorn: an Ancient Relics Story ; https://steamcommunity.com/sharedfiles/filedetails/?id=1771058495 (patch 2.7.1)

44 - advancedascension ; https://steamcommunity.com/sharedfiles/filedetails/?id=1199002146 (patch 2.7.1)

45 - !!Modifiers fix(2.6.*) ; https://steamcommunity.com/sharedfiles/filedetails/?id=1688887083 (patch 2.6* éventuelle maj à voir)

46 - LR303's GLaDOS Advisor ; https://steamcommunity.com/sharedfiles/filedetails/?id=1239558744 (patch 2.6* éventuelle maj à voir)

47 - Bigger Sliders ; https://steamcommunity.com/sharedfiles/filedetails/?id=2032225771 (patch 2.7.1)

48 - Even More Origins; https://steamcommunity.com/sharedfiles/filedetails/?id=1998204784 (patch 2.6* éventuelle maj à voir)

49 - Origins Extended (2.7 ready!) ; https://steamcommunity.com/sharedfiles/filedetails/?id=2030472413 (patch 2.7.1)

50 - Space Communism Updated ; https://steamcommunity.com/sharedfiles/filedetails/?id=2033874759 (patch 2.6* éventuelle maj à voir)

51 - Taskforce Xeno: Alien Invasion Origin ; https://steamcommunity.com/sharedfiles/filedetails/?id=2032299408 (patch 2.6* éventuelle maj à voir)

52 - Psionics Re-Re-Expanded ; https://steamcommunity.com/sharedfiles/filedetails/?id=2019820989 (patch 2.6* éventuelle maj à voir)

53 - The Decadence of Sanity--An Expanded Feature on Shroud ; https://steamcommunity.com/sharedfiles/filedetails/?id=1588842850 (patch 2.6* éventuelle maj à voir)

54 - District Overhaul 2 ; https://steamcommunity.com/sharedfiles/filedetails/?id=2026330346 (patch 2.6 en attente de maj)

55 - Harvester Nanites Origin & Distant Stars Overhaul ; https://steamcommunity.com/sharedfiles/filedetails/?id=1971940221 (patch 2.6* éventuelle maj à voir)

56 - A Deadly Tempest (2.6) ; https://steamcommunity.com/sharedfiles/filedetails/?id=2028826064 (patch 2.7)

57 - Few New Origins ; https://steamcommunity.com/sharedfiles/filedetails/?id=2040796138 (patch 2.7.1)

58 - Additional Traits ; https://steamcommunity.com/sharedfiles/filedetails/?id=681576508 (patch 2.7.1)

59 - Cute trait ; https://steamcommunity.com/sharedfiles/filedetails/?id=1235415812 (patch 2.6* éventuelle maj à voir)

60 - Inflection Point - Ecumenopolis Origin Mod ; https://steamcommunity.com/sharedfiles/filedetails/?id=2047275038 (patch 2.6* éventuelle maj à voir)

61 - Morbid Origins ; https://steamcommunity.com/sharedfiles/filedetails/?id=2053871467 (patch 2.6* éventuelle maj à voir)

62 - Nomads: The wondering Void Farers 2.6 ; https://steamcommunity.com/sharedfiles/filedetails/?id=2038997944 (patch 2.6* éventuelle maj à voir)

63 - Pantheons of the Void ; https://steamcommunity.com/sharedfiles/filedetails/?id=2052636859 (patch 2.7.1)

64 - Complex Origins ; https://steamcommunity.com/sharedfiles/filedetails/?id=2060393654 (patch 2.7.1)

65 - Venture Politics - More Megacorp Civics ; https://steamcommunity.com/sharedfiles/filedetails/?id=2029348400 (patch 2.6* éventuelle maj à voir)

66 - [FR] Mickey conseiller ; https://steamcommunity.com/sharedfiles/filedetails/?id=1892415483 (patch 2.5* éventuelle maj à voir)

67 - SE - Human - Hair ; https://steamcommunity.com/sharedfiles/filedetails/?id=2037107797 (patch 2.6* éventuelle maj à voir)

68 - The Wandering Ghost (Storypack) ; https://steamcommunity.com/sharedfiles/filedetails/?id=2047799390 (patch 2.6* éventuelle maj à voir)

69 - Stellaris List EXtender - SLEX ; https://steamcommunity.com/sharedfiles/filedetails/?id=2054717582 (patch 2.6* éventuelle maj à voir)

70 - I am the Senate! ; https://steamcommunity.com/sharedfiles/filedetails/?id=2085908386 (patch 2.7.1)

71 - Federations Expanded ; https://steamcommunity.com/sharedfiles/filedetails/?id=2065121501 (patch 2.6.3, probablement incompatible sans maj)

72 - CABAL Advisor ; https://steamcommunity.com/sharedfiles/filedetails/?id=1293884632 (patch 2.5* éventuelle maj à voir)

73 - GDI EVA Advisor ; https://steamcommunity.com/sharedfiles/filedetails/?id=2088868922 (patch 2.6* éventuelle maj à voir)

74 - Basic Ordinary Origins ; https://steamcommunity.com/sharedfiles/filedetails/?id=2027051983 (patch 2.6* éventuelle maj à voir)

75 - Cybrxkhan's Assortment of Namelists for Stellaris ; https://steamcommunity.com/sharedfiles/filedetails/?id=682691478 (patch 2.6* éventuelle maj à voir)

76 - Diverse Rooms ; https://steamcommunity.com/sharedfiles/filedetails/?id=902204956 (patch 2.5* éventuelle maj à voir)

77 - Princess Connect Re:Dive Portraits ; https://steamcommunity.com/sharedfiles/filedetails/?id=2079890999 (patch 2.6* éventuelle maj à voir)

78 - Playable Fire Species! (Portraits, Perks, Traits, Megastructure) ; https://steamcommunity.com/sharedfiles/filedetails/?id=2079074663 (patch 2.6* éventuelle maj à voir)

79 - Playable Gas Species (Portraits, Traits, Origin, Relic & Story!) ; https://steamcommunity.com/sharedfiles/filedetails/?id=2061733059 (patch 2.6* éventuelle maj à voir)

80 - SCP Universe Flags ; https://steamcommunity.com/sharedfiles/filedetails/?id=1877480687 (patch 2.5* éventuelle maj à voir)

81 - Dimension technology package 维度技术扩展包 beta 1.2.2 ; https://steamcommunity.com/sharedfiles/filedetails/?id=2036924448 (patch 2.6* éventuelle maj à voir + traduction du chinois à faire)

82 - !! 00 Performance ; https://steamcommunity.com/sharedfiles/filedetails/?id=1882139456 (patch 2.7.1)

83 - !! 00 Performance Plus ; https://steamcommunity.com/sharedfiles/filedetails/?id=1990646390 (patch 2.7.1)

84 - !! 00 Infinite Stellaris Framework ; https://steamcommunity.com/sharedfiles/filedetails/?id=1943060017 (patch 2.7.1)

85 - !! 00 Performance Statistics ; https://steamcommunity.com/sharedfiles/filedetails/?id=2029267357 (patch 2.7.1)

86 - !! 00 Crisis Master <temporary outdated> ; https://steamcommunity.com/sharedfiles/filedetails/?id=2036051710 (patch 2.6.3 maj en attente de parution pour être compatible)
  
87 - !! 00 Performance Universial Compatibility ; https://steamcommunity.com/sharedfiles/filedetails/?id=1990079757 (patch 2.7.1)

88 - !!!Universal Resource Patch [2.4+] ; https://steamcommunity.com/sharedfiles/filedetails/?id=1595876588 (patch 2.7.1)

89 - UI Overhaul Dynamic ; https://steamcommunity.com/sharedfiles/filedetails/?id=1623423360 (patch 2.6* éventuelle maj à voir)

90 - Tiny Outliner v2 ; https://steamcommunity.com/sharedfiles/filedetails/?id=1610578060 (patch 2.6* éventuelle maj à voir)

91 - UI Overhaul Dynamic + Tiny Outliner v2 ; https://steamcommunity.com/sharedfiles/filedetails/?id=1628912584 (patch 2.7.1)

92 - UI Overhaul Dynamic + Pantheons of the Void ; https://steamcommunity.com/sharedfiles/filedetails/?id=1917973338 (patch 2.7.1)

93 - UI Overhaul Dynamic + Planetary Diversity ; https://steamcommunity.com/sharedfiles/filedetails/?id=1623423504 (patch 2.7.1)

94 - UI Overhaul Dynamic + Plentiful Traditions ; https://steamcommunity.com/sharedfiles/filedetails/?id=1658823494 (patch 2.7.1) [Un bug d'affichage persiste sur les slots d'atouts d'ascensions, ordre de pleintiful et UI overhaul à revoir]

95 - More Flags ; https://steamcommunity.com/sharedfiles/filedetails/?id=717220943 (patch 2.3* éventuelle maj à voir)

96 - Origin - The Great Mistake ; https://steamcommunity.com/sharedfiles/filedetails/?id=2093276523 (patch 2.7.1)

97 - [Anime and Game] DanMachi Species Mod 2.7~ ; https://steamcommunity.com/sharedfiles/filedetails/?id=2045153355 (patch 2.7.1) [Images de chargement à retirer]

98 - [Anime and Game] Shōjo☆Kageki Revue Starlight Species Mod 2.7~ ; https://steamcommunity.com/sharedfiles/filedetails/?id=2045565457 (patch 2.7.1) [Images de chargement à retirer]


## Collaborateur

Pull Review :

* DocteurHashley
* Vidocq56
* TrazynInfini

Traduction :
