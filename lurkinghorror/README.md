# The Lurking Horror Source Code Collection

The Lurking Horror is a 1987 interactive fiction game written by Dave Lebling and published by Infocom.

Further information on the Lurking Horror:

* [Wikipedia](https://en.wikipedia.org/wiki/The_Lurking_Horror)
* [The Digital Antiquarian](https://www.filfre.net/2015/10/the-lurking-horror/)
* [The Interactive Fiction Database](http://ifdb.tads.org/viewgame?id=jhbd0kja1t57uop)
* [The Infocom Gallery](https://gallery.guetech.org/lurking/lurking.html)
* [IFWiki](http://www.ifwiki.org/index.php/The_Lurking_Horror)

__What is this Repository?__

This repository is a directory of source code for the Infocom game "The Lurking Horror", including a variety of files both used and discarded in the production of the game. It is written in ZIL (Zork Implementation Language), a refactoring of MDL (Muddle), itself a dialect of LISP created by MIT students and staff.

The source code was contributed anonymously and represents a snapshot of the Infocom development system at time of shutdown - there is no remaining way to compare it against any official version as of this writing, and so it should be considered canonical, but not necessarily the exact source code arrangement for production.

__Basic Information on the Contents of This Repository__

It is mostly important to note that there is currently no known way to compile the source code in this repository into a final "Z-machine Interpreter Program" (ZIP) file. There are .ZIP files in some of the Infocom Source Code repositories but they were there as of final spin-down of the Infocom Drive and the means to create them is currently lost.

Throughout its history, Infocom used a TOPS20 mainframe with a compiler (ZILCH) to create and edit language files - this repository is a mirror of the source code directory archive of Infocom but could represent years of difference from what was originally released.

In general, Infocom games were created by taking previous Infocom source code, copying the directory, and making changes until the game worked the way the current Implementor needed. Structure, therefore, tended to follow from game to game and may or may not accurately reflect the actual function of the code.

There are also multiple versions of the "Z-Machine" and code did change notably between the first years of Infocom and a decade later. Addition of graphics, sound and memory expansion are all slowly implemented over time.

__What is the Purpose of this Repository__

This collection is meant for education, discussion, and historical work, allowing researchers and students to study how code was made for these interactive fiction games and how the system dealt with input and processing. It is not considered to be under an open license.

Researchers are encouraged to share their discoveries about the information in this source code and the history of Infocom and its many innovative employees.

__Some Trivia and Notes on this Repository__

* The game takes place primarily in Building 20, a "temporary" building that was built on the MIT campus for World War II-related research and which continued to be used by research and academic work until it was demolished in 1998. (Citation: https://en.wikipedia.org/wiki/Building_20)
