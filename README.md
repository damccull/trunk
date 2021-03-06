RhostMUSH
=========

(This repository is a git clone of the main SVN repository at google code. It does not match the official rhost git repository which is a long time out of date.)

RhostMUSH is a security hardened text-based multiplayer RPG server initially based on TinyMUD. It features granular permission systems, a wide and varied set of tools for building your online world, and a continuously developing codebase.

RhostMUSH has a developer hangout MUSH at iweb.localecho.net 4201 - please feel free to connect there if you want to reach us, or need help with anything.

##Getting Started
* Download one of the releases and extract it.
* Ensure this path exists {Extraction Folder}/Rhost/Server/game/data. If the data folder doesn't exist, create it.
* Change your directory to {Extraction Folder}/Rhost/Server
* Type 'make confsource'
* Select the options you want and choose 'r'
* Watch your mush build
* Change your directory to {Extraction Folder}/Rhost/Server/game
* Edit netrhost.conf according to your wishes and close it
* Type ./Startmush
* Connect to the server and port you specified
* Login as '#1' with the password 'Nyctasia'
* Type '@newpass me=<a new password>' in the mush client
* Type @dump in the mush client
* Type @shutdown in the mushclient
* Restart your mush with ./Startmush in the shell and go play


##Online help files for RhostMUSH exist.

###Mortal Help
[Mortal Help HTML format][1]

###Wizard Help
[Wizard Help HTML format][1]

##FANSI Support

Note: FANSI support is based on an older version of the game. I have no intention of updating it further. If you wish to update it, please feel free to send a pull request.

This repository has a branch of RhostMUSH that supports the [FANSI 2.0 standard][4]. While the basic version supports xterm256 colors and certain accent characters already, the FANSI branch adds the ability for all of the FANSI 2.0 extended characters in the IBM/OEM character set. It also supports the Mud Extension Protocol(MXP)'s COLOR tag to enable 256 colors on clients which support MXP but do not support xterm256. See the wiki for help with FANSI options. Download the FANSI release under the [Releases][3] tab.


[1]: http://rhostmush.com/autohelp/help.html "Mortal Help"
[2]: http://rhostmush.com/autohelp/wizhelp.html "Wizard Help"
[3]: https://github.com/damccull/RhostMUSH/releases "Releases"
[4]: http://fansi.org/Specification.aspx "FANSI 2.0 Specification"
