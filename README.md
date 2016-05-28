# MK8-Editor
An editor for the WiiU game, Mario Kart 8. It currently only edits course BYAMLs, which contain info about the objects in courses.

## Setup
This requires the following:
 - **A dump of Mario Kart 8's files** - This is what MK8-Editor operates on, and you can get them with [ddd](https://gbatemp.net/threads/ddd-wiiu-title-dumper.418492/). ddd is a Wii U application for the [Homebrew Launcher](https://gbatemp.net/threads/homebrew-launcher-for-wiiu.416905/). You can use it by extracting ddd and the Homebrew Launcher's files to an SD card, putting that in your Wii U, going to http://loadiine.ovh/, and selecting Homebrew Launcher RC1.
 - **Python 2.7 32-bit** - Go [here](https://www.python.org/downloads/), and click Download Python 2.7.11. Install it to C:\Python27. You can keep the default settings, but adding python.exe to your path will make things easier later on.
 - **PyQt4** - Go [here](https://sourceforge.net/projects/pyqt/files/PyQt4/PyQt-4.11.4/), click PyQt4-4.11.4-gpl-Py2.7-Qt4.8.7-x32.exe, and run the installation. If it complains about not having Python, confirm that you are on a 32-bit version of Python (We use this because of PyOpenGL), and that you are on version 2.7.11.
 - **PyOpenGL** - Open a command prompt (Search for cmd.exe). If this is the first time you've installed any version of Python, type **pip install PyOpenGL**. If you have multiple installations of Python on your computer, type **C:\Python27\Scripts\pip.exe install PyOpenGL**.
 - **A hex editor** - [HxD](https://mh-nexus.de/en/downloads.php) will do.

This application uses Python 2.7, and not 3.5, so type **python -V** into a command promt.
If it outputs anything other than Python 2.7.11, you'll run launch.bat.

If running **python -V** did output Python 2.7.11, you should be able to double click on main.py and be fine.

## Usage
