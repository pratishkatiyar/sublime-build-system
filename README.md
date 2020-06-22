# sublime-build-system

To install sublime text 3 in ubuntu follow the file(sublime text 3 installation)
-> Open Terminal(Ctrl+Alt+T)
-> When it opens, run command to install the key:
    -> wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
-> Then add the apt repository via command:
    -> echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
-> Finally check updates and install sublime-text via your system package manager or by running commands: 
    -> sudo apt-get update
    -> sudo apt-get install sublime-text
    


Once installed, launch it from your desktop app launcher.


A sublime build system for C++ and Python in ubuntu.


To use it, Go to Tools->Build System->New build system and paste the code there. Save it with any name. Go to tools->Build System and the select your Build System.
