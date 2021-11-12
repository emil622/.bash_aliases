# Developer tool belt
A file for useful bash command aliases used in a day to day software development process


## Installation
This assumes you use the default _.bash_profile_ file and is placed in default home folder
More options might be supported in the future

1. Clone this repo in your home folder
2. Run `chmod 774 .bash_profile_aliases/install.sh` (this will enable `install.sh` to have run permission)
3. Run `./.bash_profile_aliases/install.sh` (will add a line in your _.bash_profile_ to source aliases file. Make sure you only run it once!)
4. Restart terminal and enjoy


## Commands reference
This commands can be run in terminal from any path

### Xcode indexing
Indexing can take a lot of processing bandwidth so sometimes might be useful to disable it.
Useful when switching git branches or you need faster build process for tests or archiving/building.
Restart is required 

- `startXcodeIndexing`
- `stopXcodeIndexing`

### Finder hidden files
Mac OS has a bunch of hidden files which sometimes can be useful to see them in finder instead of just the terminal.

- `showHiddenFiles`
- `hideHiddenFiles`
