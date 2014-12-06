anihilist
=========
a ncurses client for anilist.co

![](http://moc.sirtetris.com/anihilist.png)

features
--------
* display anilist.co watching list
* change number of watched episodes\*

setup
-----
* write your anilist user[name|id] into the file `username`
* run `python3 anihilist.py`
* the program will ask you to generate an auth code on [this site](http://moc.sirtetris.com/anihilist/echocode.php)
* do so, paste it in the prompt, hit \<ENTER>
* from this point on, just run `python3 anihilist.py` to start anihilist

usage
-----
* **k** -> navigate up
* **j** -> navigate down
* **l** -> increase watched episodes count by one\*
* **h** -> decrease watched episodes count by one\*
* **i** -> toggle ID layer
* **q** -> quit

\* planned, not yet implemented
