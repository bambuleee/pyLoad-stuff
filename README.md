[[Hook] HDAreaOrg.py](HDAreaOrg.py)
==============
 - eigenständiger Moviefetcher
 - Sucht jede Kategorie nach neuen Filmen ab und fügt diese pyLoad hinzu
 - Minimum Rating für Queue und Collector
 - Definiere deine bevorzugten Hoster
 - Schliesse ungewollte Genre aus
 - Pushover und PushPullet Notifications.

[[Hook] SJ.py](SJ.py)
==============
 - Sucht den serienjunk**s rss nach neuen Episoden ab.
 - Definiere Serie und deren Qualität, Sprache, ReleaseGroup individuell über eine Textdatei fest
 - erstelle eine SJ.txt in deinem pyload ordner.
```.englisch.*gravity.falls.*720p.*
.englisch.*game.of.thrones.*1080p.*
.deutsch.*sherlock.*720p.*
.deutsch.*boardwalk.empire.*720p.*
.deutsch.*mord.mit.aussicht.*720p.*
```
 - Pushover und Pushbullet notifications

[[Hook] FileBot.py](FileBot.py)
==============
This Hook uses the FileBot program from rednoah to have downloaded Movies/Series/Animes automatically renamed and sorted.

download FileBot.py and copy it into your pyload/userplugins/hooks folder.
restart pyload and configure it.


[FileBot.sh](filebot.sh)
==============
Some additional stuff happening to the moved File
 - modify creation date (to have it stored "recently added" in XBMC)
 - make it read / writeable for everyone (something i need to do)
 - send email/pushbullet with location of the file and changed filesize (nice to have)
 

Have fun
Gutz-Pilz
