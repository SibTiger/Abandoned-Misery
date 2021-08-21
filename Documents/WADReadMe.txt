===========================================================================
Archive Maintainer      : Would you kindly replace 'amisery.zip' from 
                            [ levels/doom2/deathmatch/Ports/a-c/amisery.zip ]
                            with this file.  Thank you!
Advanced engine needed  : GZDoom 2.0 or later (Recommended)
Primary purpose         : Deathmatch
===========================================================================
Title                   : Abandoned Misery
Filename                : AMisery.pk3
Release date            : 23 June 2016
Author                  : Nicholas "Tiger" Gautier
Email Address           : SibTiger_and_Life@Hotmail.com
Other Files By Author   : TGRDM1
                          TGRDM2
                          TGRCP1
                          STFBall2
Misc. Author Info       : I love Siberian Tigers :)

Description             : This map was included in my huge project
                           'TGRDM3'(Morgenstern) that originally started
                           back in 2007, but I finally decided to kill the
                           project on the 26 October 2014.  The development
                           time was going to take several more years to
                           complete, and making maps that uses 3D Objects -
                           heavily - on a 2.5 game engine is overly
                           complicated along with its limitations. 
                           Abandoned Misery was originally half-way designed
                           back in 2010, but later completely redesigned in
                           2013 (which is the version released).  I honestly
                           believe that this is the first - real successful
                           Deathmatch map I have ever created in my entire
                           history of Doom modding.  Call me bias, but I
                           have rejected approximately 37 maps that I have
                           created for the TGRDM3 project, but this map is
                           one of the survivors in the new stock set.  I
                           hope others enjoy this map and possibly use it
                           for other projects.
                           
                           Revision Update (23 June. 2016)
                            This is a revision update from the last known release.
                            Updates:
                                This update addresses several issues and minor changes that were resolved in the TGRDM3 project and has been imported onto this project.
                                Imported the maps from TGRDM3 to AMISERY: Abandoned Misery and Abandoned Misery [Lite].  This is an updated version of the maps previously released back in 2014.
                                    Notable fixes: Jump Pads, Camera Textures, 3D Teleporter support
                                    Various and minor changes are also included.
                                    Any specialized TGRDM3 features that were not present in AMISERY were excluded.
                                    For example, Jump Pad sparkles, various sounds, ring spawners, and others, were excluded.
                                Fixed the Grenade's bouncing sound.  Previously, this did not work as intended.
                                Grenade now inherits from the Grenade Class defined in ZDoom.
                                Updated the Performance Note
                                Updated the texture credits.
                                
                           Revision Update (13 September. 2015):
                            This is a revision update from the last known release.
                            Updates:
                                Added duplicate version of 'Abandoned Misery' (MAP01) -> 'Abandoned Misery [Lite] (MAP02).
                                    This map is designed primarily to resolve frame rate performance issues by removing some resource intensive features.
                                    Also, with removing such features such as floor reflection and mirrors, this should be less confusing to players as it - 
                                    could be possible for players to mistake themselves as an opponent within the game.
                            
                           Revision Update (12 September. 2015):
                            This is a revision update from the last known release.
                            Updates:
                                Imported the ZMapInfo lumps, yet modified, that was originally from the TGRDM3 project.
                                Replaced the map 'Abandoned Misery' with the version from the TGRDM3 repository.  This mainly (and should only) include weapon and THING placements.
                                Imported the competitive weapon stock set that was previously in the TGRDM3 repository.  This effectively means that all of the weapons used within the map, contains very different properties based on the original Doom game itself.  For example, rockets are much faster, shotguns have a vertical and horizontal spread, super shotgun has a slightly tighter spread, and much more.
                           
                           Revision Update (31 December. 2014):
                            This is a revision update from the last known release.
                            Updates:
                                Added Fog using resources within the Realm667 site.
                                Added Sector Fog
                                Added Rain using resources within the Realm667 site.
                                Added splashes using Enjay's "Splashes" resource mod file.
                                Added one ogg music file from 'Shane Strife'. (see \Documents\Credits.txt for more details)
                                General map fixes and updates
                                    For example; the glass ceilings where not set properly with the currently used sky.
                                        Some instant death sectors where not set properly.
                                        Texture alignment
                           
                           Performance Notes:
                                This map might be rather resource and rendering
                                intensive on various systems abroad.  Here is a
                                few Console Variables that could help a bit by
                                disabling some special features based on the
                                GZDoom engine:
                                        Line Mirrors --> GL_Mirrors (or R_DrawMirrors for Software Renderer.)
                                        Sector Reflections --> GL_Plane_Reflection
                                        Dynamic Lights --> GL_Lights
                                        Draw Translucency --> R_DrawTrans
                                        Rendering Precision --> GL_Render_Precise

Additional Credits to   : Affliction - Created a python script which helped
                            to identify duplicated images.
                            http://pastebin.com/4Tv1mfxj
                          Mazter - Assisted and shared a tool that
                            compresses images using 'Image Catalyst'
                          Qent - Helping me with testing on the Zandronum
                            engine.
                          Tribeam - For being Tribeam
                          Edward850 - Helped me fix a really odd bug in the
                            map, and ideas on presentation.
                          Eruanna - Giving me a forum section from the DRD Team
                            site for the TGRDM3 project.
                            project.
                          MaxED - Making Doom Builder 2 even better with
                            GZDoom Builder editor.  If it wasn't for GZDoom
                            Builder, editing would feel like a horror'ish
                            nightmare with managing over 600 3D Objects in
                            one map and having to deal with (G)ZDoom specific
                            features at the same time.
                          CodeImp - Making Doom Builder 2 and what started
                            it all (at least for me) Doom Builder.
                          Graf Zahl - Continuing work on the GZDoom engine.
                          Zandronum Dev. Team - Continuing work on making
                            SkullTag better and with a new vision.
                          DeathZ0r - Made a tutorial back in 2004 in
                            regards to making Deathmatch maps; a copy of the
                            tutorial can be found in the provided link:
                            http://zandronum.com/forum/showthread.php?tid=5182&pid=76221#pid76221
                          Enjay - Updated and yet made publicly available for everyone
                            to use, Splashes.
                            http://forum.zdoom.org/viewtopic.php?p=670357#p670357
                          Tormentor667 (and Realm667 contributors) - Created
                            and made publicly available for everyone to use,
                            Fog and rain special effects.
                            http://www.realm667.com/
                          Shane Strife - Created and made publicly available for
                            everyone to use, Doom 2 'High Definition' (NOT REMIXED) music.
                            http://forum.zdoom.org/viewtopic.php?p=472461#p472461
                                NOTE: Property of the contents belong to the respected
                                    creators and maintainers.  Original music by id Software.
                                    (see \Documents\Credits.txt for more details)
                          ID Software - Do I need to add a description for
                            the obvious? ;)
                          
                          
                          
                          TEXTURES
                          -------------------------
                          This a brief list of texture credits, for more information
                          and links to the resources, please see the texture documentation
                          located in the /documents/textures/ in this .pk3 archive.
                          Too Much Brown (Build 1) [2mbrown]
                            http://www.doomworld.com/idgames/?file=graphics/2mbrown.zip
                          Skulltag Community Domination Project [STDOM]
                            https://www.doomworld.com/idgames/deathmatch/skulltag/stdom
                          Requiem [REQUIEM]
                            https://www.doomworld.com/idgames/levels/doom2/megawads/requiem
                          Doom Textures For Doom II [d1gfxd2]
                            http://www.doomworld.com/idgames/?file=graphics/d1gfxd2.zip
                          deConstruct Industrial Textures [decontex]
                            http://www.doomworld.com/afterglow/textures/zips/decontex.zip
                          DarkBase Texture Wad (dgdbtxtr.wad) [DGDBTXTR]
                            http://www.doomworld.com/afterglow/textures/zips/dgdbtxtr.zip
                          Erratic Texture Pack 1 [erattex1]
                            http://www.doomworld.com/afterglow/textures/zips/erattex1.zip
                          Gothic DeathMatch (II) Graphical Resource PWAD [GOTHICTX]
                            http://www.doomworld.com/afterglow/textures/zips/gothictx.zip
                          Graphtallica Texture Pack for Doom2 #1 [graphtx1]
                            http://www.doomworld.com/afterglow/textures/zips/graphtx1.zip
                          Celtic Shrine Texture Set for Doom2 [celticsh]
                            http://www.doomworld.com/afterglow/textures/zips/celticsh.zip
                          Graphtallica Texture Pack for Doom2 #3 [graphtx3]
                            http://www.doomworld.com/afterglow/textures/zips/graphtx3.zip
                          mortres [mortres]
                            http://www.doomworld.com/metabolist/ftp/doom2/mortres.zip
                          Recoloured Doom and Doom 2 textures v2 [nb_recol]
                            http://doomworld.com/idgames/?id=14675
                          5th Episode textures (Doom 2 version) [nb5texd2]
                            http://www.doomworld.com/afterglow/textures/zips/nb5texd2.zip
                          Parallel Phobos Texture Pack [pptex]
                            https://www.doomworld.com/idgames/graphics/pptex
                          Crucified Dreams [crudream]
                            https://www.doomworld.com/idgames/levels/doom2/deathmatch/Ports/megawads/crudream
                          Doom Noir [doomnoir]
                            https://www.doomworld.com/idgames/graphics/doomnoir
                          NMN Corporation Texture Set Part 1 [NmnCorp1]
                            http://doomworld.com/idgames/?id=14345
                          Sabbat Martyr Deathmatch [smdm]
                            http://www.doomworld.com/idgames/?file=levels/doom2/deathmatch/Ports/megawads/smdm.zip
                          Duel32f [duel32f]
                            https://www.doomworld.com/vb/post/1549742
                          Ogro Texture Pack for Doom2 [ogrodtex]
                            http://www.doomworld.com/afterglow/textures/zips/ogrodtex.zip
                          psyren textures [psytex]
                            http://www.doomworld.com/afterglow/textures/zips/psytex.zip
                          The Return [RETRES]
                            http://www.doomworld.com/idgames/?file=themes/TeamTNT/return/retres.zip
                          doompotp [doompotp]
                            http://realm667.com/index.php/repository/texture-stock-mainmenu-152/1107-doom-potpourri-texs?catid=55%3Adoom-style
                           drdrtextures [drdrtextures]
                           http://realm667.com/index.php/repository/texture-stock-mainmenu-152/1353-drdoctor-texture-pack?catid=55%3Adoom-style
                          Dusk's Texture Packv [dtexpak]
                            http://realm667.com/index.php/repository/texture-stock-mainmenu-152/1436-dusks-texture-pack?catid=55%3Adoom-style
                          Baker's Legacy Texture Pack [BAK_LEG]
                            http://realm667.com/index.php/repository/texture-stock-mainmenu-152/752-bakers-legacy-texture-pack?catid=56%3Aheretic--hexen-style
===========================================================================
* What is included *

New levels              : 2
Sounds                  : Yes
Music                   : Yes
Graphics                : Yes
Dehacked/BEX Patch      : No
Demos                   : No
Other                   : No
Other files required    : Recommended but not required, Ghastly_dragon's Marine Skins
                           for Zandronum users -- ZDoom support requires a bit more work
                           http://forum.zdoom.org/viewtopic.php?p=469284#p469284


* Play Information *

Game                    : Doom 2
Map #                   : MAP01 and MAP02 [Lite version]
Single Player           : Player starts only
Cooperative 2-4 Player  : No
Deathmatch 2-4 Player   : Designed for
Other game styles       : None
Difficulty Settings     : Not implemented


* Construction *

Base                    : New from scratch
Editor(s) used          : GZDoom Builder, Notepad++, and various other
                          tools
Known Bugs              : One of the mirrors does produce a HOM due to not
                           having a larger rendering void, this effect
                           probably wont be easily noticeable.
                          
                          If using the Zandronum engine, please do use version 3.0 or later.  This map and it's required assets is not compatible with any build before version 3.0.
May Not Run With...     : ZDoom's software rendering engine, this is due to
                           the sloped 3D Objects.  But,  this is only a
                           visual issue, the map will still work as expected
                           regardless.


* Copyright / Permissions *

Authors MAY use the contents of this file as a base for modification or
reuse.  Permissions have been obtained from original authors for any of
their resources modified or included in this file.

You MAY distribute this file, provided you include this text file, with no
modifications.  You may distribute this file in any electronic format (BBS,
Diskette, CD, etc) as long as you include this file intact.  I have
received permission from the original authors of any modified or included
content in this file to allow further distribution.

* Where to get the file that this text file describes *

The Usual: ftp://archives.3dgamers.com/pub/idgames/ and mirrors

