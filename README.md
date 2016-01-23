## Overview
Some filelists which can help you in a web file/directory enumeration process (dirbusting) during penetration testing. These files contain lists of paths. It lists potentially can help you to find out sensitive information.

- ### **fuzz.txt**
It was gathered during many months collecting information from pentest and information security audit. Thanks [@i_bo0om](https://twitter.com/i_bo0om) for that work.

- ### **top_plus_interest.txt**
Created from [danielmiessler](https://github.com/danielmiessler)'s *Top10000-RobotsDisallowed.txt* + *InterestingDirectories.txt* without duplicates, without some garbage and without all items which contains in fuzz.txt. So you can check *fuzz.txt* for first and then *top_plus_interest.txt*. It's a harvest of the Disallowed directories from the robots.txt files of the world's top websites.

- ### **extensions.txt**
Contains some file exstensions which cant help you to find backup of selected file. Just change %name% with filename and/or %ext% to extension.
