# debianmini

Running Debian 12 minimal on WSL2 Windows 11<br>
Github file size limited to 25MB so i use 7zip to make the tar file smaller.<br>
Extract the debian.7z first.<br>
Then just import debian.tar file into WSL2.<br><br>

<b><h1>Requirement</h1></b><br>
1. WSL2 must be installed first!
2. Download debian.7z ,extract it using <a href="https://www.7-zip.org/">7zip</a> apps and copy the tar file to your c:\debian.tar
3. create Folder c:\WSL
4. Then create debian folder for Distro c:\WSL\debian
5. open cmd
6. Import debian.tar using command as below:

&nbsp; &nbsp; &nbsp; &nbsp; wsl --import debian c:\WSL\debian c:\debian.tar<br>

7. Run your debian using command as below:

&nbsp; &nbsp; &nbsp; &nbsp; wsl -d debian<br><br>
&nbsp; &nbsp; &nbsp; &nbsp; Enjoy!
