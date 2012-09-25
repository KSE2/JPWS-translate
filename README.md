JPWS-translate
==============

Translation of the JPasswords project (application). http://jpws.sourceforge.net/jpasswords.html

Feel free to engage in a translation work for JPasswords. Even if a language will not be integrated into the program, in future it will be possible to add custom language files within an individual installation.
On schedule I'm looking for FRENCH to be added to the program file.

Rules and Regulations
---------------------

Translation is not trivial. For at least one reason: impermanence! With a translation delivered, I expect you are willing to maintain it for some time, otherwise it will likely get disabled with the next release.
There are 2 major parts of language files: a) the core interface file, stored as ".properties" files, and b) the html text files, most of them belonging to the Help system. As a minimum for a translation to be activated in a program release, the core files have to be completely translated. Other files can be added on a "per file" base while I keep English as the default language for untranslated files.
The reward for a (maintained) translation is a mention in the contribution acknowledgments, if you wish for it.

Technical
---------

.properties files are currently in ISO-8859-1. There are plans, however, to move this part into UTF-8 as well. The current format kind of unnaturally restricts the range of possible languages. Protests are welcome!
Html files are in UTF-8 format (or where they are not, they should be!).

There is a convention about directories here. 
"Library" contains the system files as currently accepted (integrated into the program). This you shouldn't modify and is maintained by the developer.
"work-in-progress" is the space for translation development. 

In order to commence working, you have to download the data set. The recommended procedure is: 
- create a GitHub account
- "Fork" this project
- download from your fork using Git (very useful, will be taught in primary school soon!)
- translate
- upload your work to your fork
- send me a "pull-request" via a GitHub button
If this is asking too much, you can send me the results directly to Wolfgang Keller 9103784@gmx.de.
 