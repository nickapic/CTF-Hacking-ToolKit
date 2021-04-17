Just a small repoistry i am making for some of the tools i found usefull while doing CTF's and also HTB/THM Boxes.

### Web Shells :

#### RFI to RCE : knock.txt
Main Source : https://github.com/namansahore/Remote-File-Inclusion-Shell/blob/master/knock.txt 

This is a script i found called knock.txt which can be used to get RCE from RFI's on a machine and it also works in the case if the RFI is appending a .php extension at the end of the file just rename the file to knock.php and in the RFI call it as http://IP/knock

#### Windows PHP Web Shell : windowswebshell.php

Main Source : https://gist.github.com/joswr1ght/22f40787de19d80d110b37fb79ac3985

Here is a small little shell to little html/php web shell that works on windows ideally a lot of php rev shells/ web shells tend to break on windows but i found this one which works great on most of the windows machines.
