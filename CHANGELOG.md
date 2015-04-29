##### 0.1 - Initial version for GNOME Shell 3.2

+ Setup and launch SSH Connections
+ Setup and launch Telnet Connections
+ Window Preference to setup connections
---
##### 0.1.1

+ It's possible to pass environment variables directly to the constructed command, allowing e.g. for sending a LC_ALL different from the native one to the remote system etc. (thanks to Grzegorz Staniak for idea)
---
##### 0.2

+ Added support to launch any application (custom and not) in and out a terminal shell. You can create your custom script and launch it from CM menu.
+ Published on Gnome Shell Extensions site
---
##### 0.3

+ Added support for opening connections in tabbed gnome-terminal
+ Backup config file on save
+ A new icon for CM (or old label configurable from Options Tab)
+ Added Options Tab to configure your extension
+ Explicitly invoked python version 2
+ Slighty changes to use commands like www.example.com | tee $HOME/ssh_logs/www.log
---
##### 0.3.1

+ Fix issue #8 "Command python2 not found.". Now it tries to launch python or python2.
---
##### 0.4

+ Reload automatically configuration if conf file is modified
+ Implement issue #9 "read ssh-config from ~/.ssh/config". It is possible now read hosts from ssh configuration
---
##### 0.5

+ Removed "Backup configuration file on save" option. Now backup automatically
+ Removed Icon/Label choice in options tabs. Now is present only icon
+ Terminator support added (http://www.tenshu.net/p/terminator.html). You can choose beetween gnome-terminal and terminator shell
---
##### 0.5.1

+ Removed "Save Conf" button. Now CM saves configuration automatically
+ Fixed a bug present in non-english environment
---
##### 0.6

+ Provide all Hosts / Apps configured in CM as CONNECTION MANAGER search results
---
##### 0.7

+ Code revamping to support different terminals
+ Guake (http://guake.org/) terminal support
---
##### 0.7.1 - 0.7.2

+ Fix icon/label of prefs dialog
+ Host / App clone functionality
---
##### 0.7.3

+ Fix GnomeShell compatibility (3.3/3.4 version). this release is no longer compatible with previous versions of gnome-shell.
---
##### 0.7.4

+ Added mosh shell (http://mosh.mit.edu/) - issue #17
+ Fix save configuration bug on drag&drop
+ Fix import SSHConfig functionality - issue #18
+ Implement Port field import - issue #19
---
##### 0.7.5

+ Added support for following terminals:
+ TMux (http://tmux.sourceforge.net/) - issue #21 (Thanks to Paul Robins)
+ urxvt, urxvt256c (http://software.schmorp.de/pkg/rxvt-unicode.html) - issue #22
+ LilyTerm (http://lilyterm.luna.com.tw/index.html) - issue #27
+ Check on installed terminals
+ link to terminal homepage in configuration window
---
##### 0.8

+ New icon (Thanks to Elisa)
+ Gnome 3.6 support
---
##### 0.8.1

+ Gnome 3.8 support
+ DConf migration to retrieve of terminal profiles
---
##### 0.8.2

+ Gnome 3.10 support
---
##### 0.8.4

+ Gnome 3.14 support
---
##### 0.8.5

+ Gnome 3.16 support
---
