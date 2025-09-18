# debianmini

Running Debian 12 minimal on WSL2 Windows 11

Just import debian.tar file into WSL2.<br><br>

<b><h1>Requirement</h1></b><br>
1. WSL2 must be installed first!
2. Download debian.tar and copy at your c:\debian.tar
3. create Folder c:\WSL
4. Then create debian folder for Distro c:\WSL\debian
5. open cmd
6. Import debian.tar using command as below:

&nbsp; &nbsp; &nbsp; &nbsp; wsl --import debian c:\WSL\debian c:\debian.tar<br>

7. Run your debian using command as below:

&nbsp; &nbsp; &nbsp; &nbsp; wsl -d debian<br><br>
&nbsp; &nbsp; &nbsp; &nbsp; Enjoy!
