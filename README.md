# XMLEdit
A Tkinter GUI to edit XML files

This is a program for reading and editing XML files

Current attributes and tag contents can be edited; no new attributes or tags can be created. This program was written specifically for wide char config files generated by MS .net, but should work with anything.

Type in a directory or browse to one using the "..." button. A list of files matching the extensions in the options file will be made and populate the dropdown. 

Selecting a file will load it.

Save a file by pressing the "Save" button or "Ctrl-s". The current file is renamed with a current timestamp, and the new file is written in it's place. A program option (set in reader_options.json) allows the program to try to match the encodeing of the source. The written file is prettified (by beautifulsoup) to make it human-readable. The BS prettify is a bit different from MS but not much. 

The program will open a file given as a command line argument, which means you can associtate this program with .xml files to open them from the explorer right click menu. 
