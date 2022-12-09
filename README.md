# Tamil_Song_Download


Simple script to Download Tamil songs from pirate mp3 song download site : ***Masstamilan***

Heavyly inspired by **bugswriter's** song download script

Pre-requisite : aria2c, Bash ?!

Get started with, 
```sh
$ sudo curl -sL "https://raw.githubusercontent.com/Venkatesan7G/Tamil_Song_Download/main/songd" -o /usr/local/bin/songd
$ sudo chmod +x /usr/local/bin/songd
$ ./songd *Url of the album page*
```
- To update "if i provide any?", just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply remove `songd` from your **$PATH**, for example `sudo rm -f /usr/local/bin/songd.

