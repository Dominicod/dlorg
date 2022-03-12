# dlorg
dlorg is a program written by Dominic O'Donnell | https://github.com/Dominicod . This program is designed to organize your downloads folder into subdirectories allowing the user to edit each extension and create new subdirectories to allow for ease of use. (Outside of having to add a new for loop due to bash not supporting multidimensional arrays.

COMMANDS:

./dlorg | Organizes files

./dlorg -v | Version of dlorg

./dlorg -h | Help section of dlorg

SETUP:

1. To run dlorg first move dlorg to your $PATH and make sure your correct terminal is
selected.

2. Change dlorg's mode with chmod +x dlorg

This program should now work.

EDIT EXTENSIONS:

1. Use your editor vim/nano/ect to enter into dlorg, find the extension you want to edit
at the top of the file and add your edits.

EDIT SUBDIRECTORIES:

1. To edit sub directories you will first add the directory to the DIRECTORIES varible.

2. Then move down to SEPERATE function and copy the for loop however changing where the copied
subdirectory varibles are located and replacing them with the new directory name. (case-sensitive)
