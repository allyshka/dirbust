## Overview
Some filelists which can help you in a web file/directory enumeration process (dirbusting) during penetration testing. These files contain lists of paths. It lists potentially can help you to find out sensitive information.

- ### ~~**fuzz.txt**~~ **dirsearch.txt**
It was gathered during many months collecting information from pentest and information security audit. Thanks [@i_bo0om](https://twitter.com/i_bo0om) for that work. At now this file also contains 'dirssearch' [dicc.txt](https://github.com/maurosoria/dirsearch/blob/master/db/dicc.txt) posted by [maurosoria](https://github.com/maurosoria).

- ### **top_plus_interest.txt**
Created from [danielmiessler](https://github.com/danielmiessler)'s *Top10000-RobotsDisallowed.txt* + *InterestingDirectories.txt* without duplicates, without some garbage and without all items which contains in fuzz.txt. So you can check *fuzz.txt* for first and then *top_plus_interest.txt*. It's a harvest of the Disallowed directories from the robots.txt files of the world's top websites.

- ### **extensions.txt**
Contains some file exstensions which cant help you to find backup of selected file. Just change %name% with filename and/or %ext% to extension.

- ### **azzz.txt**
Contains [a-zzz] range of file names witch %EXT% as extension. Very often it's helps to find something.

- ### **dibrust folder**
That files from good old java guy [DirBuster](http://sourceforge.net/projects/dirbuster/). Almost actually.