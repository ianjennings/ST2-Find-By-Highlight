# ST2 Find By Highlight

Automator service to "find in project" using Sublime Text 2

Handy when you need to find out what file is producing the rendered output. What view is generating this text?

## Usage

Just select text in any program (probably chrome), and hit whatever keyboard shortcut you define (below). 

## Install

Run the following to unhide the library folder in the current user's home directory:

    $ chflags nohidden ~/Library/


Throw the ```workflow``` folder in:

    ~/Library/Services/

if you don't have a Services folder, you should create one.
    
Then open up ```keyboard``` in ```System Preferences```, find the service named ```Project Search from Text``` (most likely under the ```Text``` group), and assign a keyboard shortcut.
