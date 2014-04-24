PoodLL Anywhere
==========

The Moodle PoodLL Anywhere plugin for Atto.
It allows the user to record audio and video or draw pictures, or snap pictures, directly into forum posts, assignment descriptions, page resource content, question descriptions, question responses and other areas. 

The recorders available are:
i) audio (red5)
ii) audio (mp3)
iii) video (red5)
iv) whiteboard
v) snapshot

They can be hidden or shown using the settings found at:
site admin -> plugins -> text editors ->  Atto html editor -> poodll anywhere

In some cases the Moodle text editor may be set to not allow uploaded files. Notably the question response area when using an essay question type, or in forum posts where attachments may be restricted or forbidden. In that situation we try to play nicely  and hide the PoodLL Anywhere icons. Using the Moodle capabilities system it is also possible to hide and
show icons depending on the user's role.

The capabilities available to be set are:
Atto/poodll:visible
Atto/poodll:allowaudiored5
Atto/poodll:allowaudiomp3
Atto/poodll:allowvideo
Atto/poodll:allowwhiteboard
Atto/poodll:allowsnapshot

Installation
===============
Install PoodLL anywhere by unzipping it and putting the "poodll" folder in
[moodle]/lib/editors/Atto/plugins  then visit your site
administration -> notifications page and follow the prompts for Moodle to install it.

It will not appear on the Atto toolbar immediately and you will need to visit:
Site administration / Plugins / Text editors / Atto HTML editor / Atto toolbar settings
Beneath the list of plugins find the "Toolbar Config" textbox. There, probably on the "files" line add the word "poodll". 
That line will then look like this:
files = image, media, poodll, 


* NOTE: PoodLL Anywhere depends on the PoodLL Filter also being installed, and will not install or work properly without it *
 
* NOTE: PoodLL Anywhere for Atto is based on PoodLL Anywhere for TinyMCE, which was funded by Birmingham City University. *

Justin Hunt
The PoodLL Guy
http://www.poodll.com
poodllsupport@gmail.com