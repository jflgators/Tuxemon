Tuxemon 0.4.1
TEAM TWO
=============

Tuxemon is a free, open source monster-fighting RPG.

![screenshot](https://www.tuxemon.org/images/featurette-01.png)

Requirements
------------

Tuxemon uses a number of open source projects to work properly:

* *python* - version 2.7, 3.5+
* *python-pygame* - python game library
* *python-pytmx* - python library to read Tiled Map Editor's TMX maps.
* *python-six* - python 2 and 3 compatibility library
* *python-pyscroll* - fast module for animated scrolling maps.
* *[neteria](https://github.com/ShadowBlip/Neteria)* - Game networking framework for Python.

*Optional*

* *libShake* - rumble library for Linux.

Installation
------------

**Windows**

[Detailed here](https://www.tuxemon.org/windows-install.html)

Windows binaries are also available in the releases.

**Ubuntu**

```sh
sudo apt install python python-pygame python-pip python-imaging python-six git
git clone https://github.com/Tuxemon/Tuxemon.git
cd Tuxemon
sudo pip install -U -r requirements.txt
python tuxemon.py
```

*Optional rumble support*

```sh
sudo apt install build-essential
git clone https://github.com/zear/libShake.git
cd libShake/
make BACKEND=LINUX; sudo make install BACKEND=LINUX
```

**Debian**

```sh
sudo apt-get install python python-pygame python-pip python-imaging git
git clone https://github.com/Tuxemon/Tuxemon.git
cd Tuxemon
sudo pip install -U -r requirements.txt
python tuxemon.py
```

**Mac OS X (Yosemite)**

```sh
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew tap Homebrew/python
brew update
brew install python
brew install sdl sdl_image sdl_ttf portmidi git
brew install sdl_mixer --with-libvorbis
sudo pip install git+https://github.com/pygame/pygame.git
sudo pip install -U -r requirements.txt 
git clone https://github.com/Tuxemon/Tuxemon.git
ulimit -n 10000; python tuxemon.py
```

**Arch Linux**

Tuxemon is available in the [AUR](https://aur.archlinux.org/packages/tuxemon-git/).

**Smartphones**
* [Android](https://www.tuxemon.org/files/builds/tuxemon-unstable-latest.apk) (APK file)

Controls
--------

##### Tuxemon
* *Arrow Keys* - Movement
* *Enter* - Select/activate
* *ESC* - Menu/Cancel

##### Map Editor

Use *Tiled* map editor: http://www.mapeditor.org/

Translations
------------

JSON translation files are now obsolete.  Please edit the po files under the
resources/l18n/ folder for new translations.  The json translation files will
be removed sometime in the future.  Thank you!

Tuxemon has support for several languages.  Because Tuxemon is a community project
and not all members are intimately familiar with or fluent in each language, there
are possible translation errors.  We also acknowledge that some translations may
have errors intentional or otherwise that could be offensive or inappropriate.

We make every effort to test using automated tools such as google translate to test
translations, but these are not perfect tools.

If you spot a translation error that is inappropriate, please open a github issue
and be respectful to the team.  We do not wish for translation errors and will do
what we can to make sure the game is fun and enjoyable to everyone.

License
-------

GPL v3+

Copyright (C) 2017 William Edwards <shadowapex@gmail.com>,     
Benjamin Bean <superman2k5@gmail.com>

This software is distributed under the GNU General Public Licence as published
by the Free Software Foundation, either version 3 of the License, or (at your
option) any later version.  See the file [LICENSE](LICENSE) for the conditions
under which this software is made available.  Tuxemon also contains code from
other sources.

External links
--------------

* Official website: [tuxemon.org](https://www.tuxemon.org)
* Official forum: [forum.tuxemon.org](https://forum.tuxemon.org/)
* IRC: [#tuxemon](ircs://chat.freenode.net/#tuxemon) on freenode ([webchat](https://webchat.freenode.net/?channels=%23tuxemon))
* Discord: [Tuxemon](https://discord.gg/3ZffZwz)
* Reddit: [/r/Tuxemon](https://www.reddit.com/r/tuxemon)
* YouTube: [Tuxemon](https://www.youtube.com/channel/UC6BJ6H7dB2Dpb8wzcYhDU3w)
* Google Plus: [+TuxemonOrg](https://plus.google.com/u/0/+TuxemonOrg)
