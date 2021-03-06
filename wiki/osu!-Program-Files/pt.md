![osu! Program Files in nutshell](Osu!sys.jpg "osu! Program Files in nutshell")

Localização
===========

Windows
-------

Por padrão `C:Program` `Filesosu!` onde "C:" é o seu Disco Rígido com osu! instalado. Para Windows 8, `C:Program` `Files(x86)osu!`.

![Folder](Folder.png "Folder") Pastas
==============================================================================================

_MACOSX
--------

**osu! para Macintosh OS.** No caso de usuários de Sistemas operacionais Windows, apenas ignore ou delete a pasta se desejar.

Chat
----

Aparece apenas se você usou "/savelog" no painel de Chat ou se você habilitou "Automatically log private messages" nas Opções. A pasta mostra suas converças particulares com outros jogadores.

The styling is `{Tab_name}-{YYYYMMDD}-{HHMMSS}` in .txt format, which basically can be opened in any word application of choice(Notepad).
**Example:** #multiplayer-20121115-040845 (/savelog at #multiplayer tab in 15th November 2012 at 0408hrs and 45secs).

Downloads
---------

Appears when you had used the "osu!direct" download service. **Holds the .osz files which you are currently downloading from osu!direct**, later to be transferred into osu!'s Songs folder as legitimate beatmaps upon completion.

Exports
-------

Appears if you used the [Skin Selector's "Export as .osk"](Options#Skin_Selector "wikilink") or [Beatmap Editor's "Export Package"](Beatmap_Editor/Menu#File "wikilink"). **Holds .osz (beatmap)/.osk (skin) file you had exported from osu!.** [For how-to, click me](Osu!_File_Formats#From_the_game "wikilink").

Localisation
------------

Appears when you had switched your Language under Graphics at Options page. **Holds translated text files which can be used each to replace the usual English text based on selected localisation.**

Replays
-------

Holds **external executable osu! replay file (.osr)**. Does not work when the beatmap linked to the replay file is missing. Holds Results data and reanimates your cursor movement during the replay. To create the .osr, press "**[F2]**" at Results screen or click on the "Save as .osr" at the Online Ranking screen (below Results screen in Solo only). Does not save multi-play elements. File size ranging around 100KB ~ 1KB. [For players who are interested to upload their replay to Youtube, see this tread](https://osu.ppy.sh/forum/t/108092).

The format is `{Local` `player` `name}` `-` `{Artist}` `-` `{Title}` `{[Difficulty]}{(YYYY-MM-DD)}` `{Game` `Mode}`
**Example:** dummytest1 - Loituma - Ievan Polkka [SPINNER-MADNESS]  (2013-08-12) OsuMania

Screenshots
-----------

**Screenshots (F12 by default) of osu!**. The saved screenshot's file extension (.jpg/.png) is based on what you set on the Options menu.

The format is `screenshot###` where "###" is the screenshot number count.

Skins
-----

Holds **user-created skins which can be used to customise your User Interface around osu! in-game.** You can download more skins from osume!.exe(osu! updater) under Skins tab or you can take a tour to the [forum's skinning palace](https://osu.ppy.sh/forum/15). Skins downloaded from osume!.exe are extracted immediately and ready to use. For forum's downloads, there are two possibility. If you get a executable osu!skin (.osk) file, directly open it and you will be forced to open osu! and directed to the "Skins Selector" screen with your new skin located at the list. If the downloaded skin is in folder form, you will have to place the folder here yourself. If it is in .zip/.rar format, you must extract it first. You can change your skins at [Options menu under Skins tab (Skin Selector)](Options#Skins "wikilink"). Please bear in mind the skin used is *only effective to your own osu! only.*

For further reference, please refer to the [Skinning](Skinning "wikilink") page. Also, "osu! by peppy" is the only skin without its folder and cannot be deleted directly.

Songs
-----

**Your compendium of osu! beatmaps**. Usually contains .osu (difficulties), .mp3/.ogg (music file), .jpg/.png/.gif (BG image), .osb (SB file) and .mp4/.flv (video file). May also contains .wav/.ogg (hitsound file) and folders (SB spites and/or skin).

The format is `{Beatmap` `number}` `{Artist}` `-` `{Song` `Title}`.
**Example:** [57950 SOUND HOLIC - Drive My Life](https://osu.ppy.sh/s/57950)

Please note that *ancient* beatmaps folders during the beginnings of osu! do not have numberings and does not follow the format. Some examples would be "[discoprince](http://osu.ppy.sh/s/1)" or "[avgn](http://osu.ppy.sh/s/66)". Special mention goes to "[tutorial](http://osu.ppy.sh/s/3756)" because every osu! player will have it when osu! is installed using the osu!installer. Also, manually created/graveyard .osz/.zip songs folders can be counted as well.

Hidden Folders
--------------

### Data

**osu!data files.** Should not be tampered.

Program files
=============

.db (Database file)
-------------------

The .db files are beatmaps' data which only osu!.exe/osu!test.exe can utilise. Notepad can open the .db files but it will be mostly made up of encrypted characters.

**osu! database**

-   collection.db (Your "Collections" in-game. You can post it to forum for others to check out your "Collections". Actual beatmaps not provided.)
-   osu!.db (osu! beatmaps' cache. You know, that long start-up loading screen before you see Song Selection?)
-   presence.db (Cache of osu!players @ Chat Console)
-   scores.db (Stores historical Local scores)

.cfg (Configuration files)
--------------------------

Configuration files or config files configure the initial settings for osu! to work. The files can be opened by Notepad.

-   osu!.cfg (osu! logic configuration.)
-   osu!.{YOUR PC NAME}.cfg ("[Options](Options "wikilink") screen". Also contains [deprecated/interesting variables and sensitive information](Osu!_Program_Files/osu!.HelloWorld.cfg "wikilink"))
    -   {YOUR PC NAME}: Your PC account name. Say, if you set your admin/user account's name as "HelloWorld", the .cfg file will be named, osu!.HelloWorld.cfg .

.exe (Application)
------------------

The main component. Click on it to start-up. The .exe files are safe to open assuming you used the osu!installer to install osu!.

-   ![Logo](logo.png "Logo") osu!.exe (Start-up osu!)
-   <img src="Osume.png" title="fig:Osume.png" alt="Osume.png" width="20" /> osume.exe (Start-up osu! updater. osu!.exe will open this itself when there is a new version. Contains Changelog and Skins (deprecated) to download. Also revives osu!.exe files)

Hidden files
------------

### ![DLL Icon](DLL_Icon.jpg "DLL Icon") .dll (application extension)

The .dll files are components of osu!.exe so ignore it.

**Base components** (For Microsoft .NET)

-   avcodec-51.dll
-   avformat-52.dll
-   avutil-49.dll
-   bass.dll
-   bass_fx.dll
-   d3dx9_31.dll
-   Microsoft.Ink.dll
-   Microsoft.Xna.Framework.dll
-   pthreadGC2.dll
-   x3daudio1_1.dll

**osu! components**

-   ~~osu!framework.dll~~
-   osu!gameplay.dll
-   osu!ui.dll
-   osu.dll

[Category:Infrastructure of osu!/PT](Category:Infrastructure_of_osu!/PT "wikilink")
