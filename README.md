# debianmini
debian 12 minimal for WSL2

Running Debian minimal on WSL2 Windows 11

Just import debian.tar file into WSL2.

Requirement
WSL2 must be installed first!
Download debian.tar and copy at your c:\debian.tar
create Folder c:\WSL
Then create debian folder for Distro c:\WSL\debian
open cmd
Import debian.tar using command as below:

wsl --import debian c:\WSL\debian c:\debian.tar

Run your debian using command as below:

wsl -d debian
Enjoy!
