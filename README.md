# Chantier de traduction fr ModPack Omega

## TODO test test test

* trad du dossier **A_Traduire**
* chk eng --> fr, voir si il n'y a pas encors des mod sans `_l_french`
* test ingame voirs si le reorga crash
* Listes des mod du pack ici et checklist pour les id's
* add - `/localisation-synced` et des sub de `/common` pour la trad.

### Pour rapelle

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

## Overwriting Vanilla Text

>To overwrite vanilla localisation keys (or keys from other mods), create a folder named "replace" inside your "localisation" folder. Localisation files in this folder will load after all other localisation files, and overwrite any duplicate keys. In this way it is not necessary to overwrite entire localisation files, as individual key entries will be overwritten by the last loaded file, LIOS (Last in, only served). It is possible to overwrite localisation without a "replace" folder, however this is not a reliable method.