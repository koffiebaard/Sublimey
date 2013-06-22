Sublimey
========

A method of project-switching for Sublime Text. The script, Sublimey, launches the Sublime project you specify as an argument, or if it's already open it will bring the projects Sublime window to the front.


How to use/install?

It's really easy:

- Create a directory somewhere to put your Sublime projects (doesn't matter where) and save the scripts there

- Save a Sublime project there, and give it a simple, short name

- Open your terminal, go to the directory and give the script executing rights:

chmod +x sublimey

- And voila, you can use it with the following syntax:

./sublimey <project-name>


How to use it with Alfred

Alfred is a productivity tool, and we can use it to switch Sublime projects (and open the project if it's not there). Just type in the name of the project and it will do everything for you. The Alfred PowerPack is not required; if you do have PowerPack you can simply hook it up to the Sublimey script. If you don't have the PowerPack, add it to Alfred like this:

- There is a .scpt file in the directory. Rename it to match the name of your project, and copy the file for every project.

e.g. "awesome.sublime-project" will need a script called "awesome.sublime.scpt"

- If you'll launch this script, it will trigger Sublimey to launch the same-named project. Since you do not have PowerPack, you can only specify custom folders and files to search through. Hence the scripts.

- Next, open Alfred preferences

- On the tab "Features", go to "Default Results". There you can specify folders to search through and filetypes to search.

- Add your Sublime project folder to the Search Scope using the "+"

- Press the "Advanced" button on the same screen and drag one of the .scpt files in there. It will recognize the filetype and make it searchable

- Voila, you can now open Sublime projects through Alfred by typing the name. When the project's already opened it will simply show you the window. 