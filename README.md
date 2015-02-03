# noter

This is a tiny little bash script to take notes from command line.

The idea came from [slashie.org](http://www.slashie.org/articles/icloud-notepad/)

## Instal

To use, download the script and add it to any path your PATH can find. To make it easy, you can use `ln -s` and link it into `/usr/local/bin/`

## Usage

### ADDING PATH

`$ noter ,add <name> <path>`

*Example:*

`$ noter ,add work ~/Desktop/mynotes.md`

### REMOVE PATH

`$ noter ,del <name>`

*Example:*

`$ noter ,del work`

### LIST PATHS

`$ noter ,list`

### ADDING EDITOR

`$ noter ,editl <editor name or path to editor>`

*Example:*

`$ noter ,editl vim`

### RECALLING EDITOR

`$ noter ,editr`



### ADDING NOTE

`$ noter .<name> <note>`

*Example:*

`$ noter .work This is just a note.`

### EDITING A NOTE

`$ noter ,edit .<name>`

*Example:*

`$ noter ,edit .work`