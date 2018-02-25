# Unix-Commands
Learning Unix Commands

Users communicate with the kernel through a program known as the shell. The shell is a command line interpreter.
All the data of Unix is organized into files. All files are then organized into directories.
These directories are further organized into a tree-like structure called the filesystem.
  whoami - displays logged in username.
  who - displays the name,date,time of logged in user.
  w - associate the full information regarding logged in user

 
  dir -   display the contents of the directory
  cd <directory name> -   to change directory.
  vi <filename.format> -  to create a file.
  cp <source filename> <destination filename> - copy file.
  read name - to read any input from console.
  echo <text> - to print text. 
    following are some useful commands for handling file.
    
    1. :w <Filename> -   writes the current Vim file to disk with name FILENAME.
    2.  v -   to select the characters in file.
    3. :r <filename> -    retrieves disk file FILENAME and puts it below the cursor position.
    4. :s/<old character>/<new character> -   to substitute character for its first occurance.
    5. :s/<old character>/<new character>/g -   to substitute character globally by adding g at the last of the command .
    6. %s/<old character>/<new character>/gc -  to find every occurrence in the whole file,with a prompt whether to substitute or not.
    7. CTRL+G -   displays your location in the file and the file status at the bottom then press following.
          gg  moves to the first line.
          G moves to last line
    8.  /  followed by a phrase searches FORWARD for the phrase.
        ?  followed by a phrase searches BACKWARD for the phrase.
           After a search type  n  to find the next occurrence in the same direction
           or  N  to search in the opposite direction.
    9.  CTRL-O takes you back to older positions, CTRL-I to newer positions.
    10. Typing  %  while the cursor is on a (,),[,],{, or } goes to its match.    
    11. :<External command>! -    to execute external commands.
    12  :r !dir -   reads the output of the dir command and puts it below the
        cursor position.
    13. ls -l - displays permission over the files.
    14. chmod - assigning/adding/removing permission on files.
    
    grep commands (Globally Regular Expression Print out)
    
    grep [option] pattern [file]
    
      options
              -c : This prints only a count of the lines that match a pattern
              -h : Display the matched lines, but do not display the filenames.
              -i : Ignores, case for matching
              -l : Displays list of a filenames only.
              -n : Display the matched lines and their line numbers.
              -v : This prints out all the lines that do not matches the pattern
              -e exp : Specifies expression with this option. Can use multiple times.
              -f file : Takes patterns from file, one per line.
              -E : Treats pattern as an extended regular expression (ERE)
              -w : Match whole word
              -o : Print only the matched parts of a matching line.

    
