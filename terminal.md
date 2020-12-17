Outline:
1. what is the terminal? what is it for?
2. how do we use the terminal? what can we do now that we're using it?
3. how are folders and files structured? how can we get a sense for it if we can't see it?

Commands:
- `cd` change directory, also takes you to the root (~)
- `cd sei` change directory into sei
- `cd ..` goes up in file structure
- `pwd` print working directory
- `mkdir new-directory` makes directory (folder) named 'new-directory'
- `touch file.js` makes javascript file named 'file'
- `mv file.js/ your-file.js` renames file
- `ls` lists files and directories in the current working directory
- `ls` lists hidden files
- `mv your-file.js/ ~/new-directory/` moves your-file into new-directory 
- `rm -rf your-file.js` deletes your-file
- `rm -r new-directory` deletes new-directory
- `clear` clears terminal 

Practice:
Move into the root directory. 
`cd ~` 
Create a directory that will hold all your work.
`mkdir seir`
Change directory into seir.
`cd seir`
Create directories for the different types of work you'll be doing.
`mkdir deliverables lessons labs projects reflection`
Create a file in lessons to save these instructions.
`touch lessons/terminal.md`
Move into the lessons directory.
`cd lessons`
List the files in lessons.
`ls`
Move into the seir directory.
`cd ..`

[ADD PICTURE OF TERMINAL HERE]

Use Homebrew to install the tree command.
`brew install tree`
- `tree` shows file structure from working directory
Print working directory.
`pwd`

[ADD PICTURE OF TERMINAL HERE]

Print the file structure.
`tree`

[ADD PICTURE OF TERMINAL HERE]

