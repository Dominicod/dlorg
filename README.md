# dlorg

This program is designed to organize your downloads folder into subdirectories allowing the user to edit each extension 
and create new subdirectories to allow for ease of use. Compatible with most Linux distros and MacOS (Monterey) 

## Test on your local machine

First you will need to clone the repo;

`git clone git@github.com:Dominicod/dlorg.git`

You will then when to move the dlorg file to your `$PATH` to access it as a terminal command anywhere.

Lastly, change the file permission to allow dlorg to execute on your machine.

`chmod +x dlorg`

## Developing

To customize how dlorg works and creates directories or what files you would like to blacklist/whitelist;

First use your code editor `nano/vim/code` into `dlorg`

Next you will want to find what you wish to change, if its file extensions this iwll be located at the top of the file.
dlorg will be able to figure out what files are removed or added and will work as intended with no further adjustment.

However if you wish to edit the subdirectories you will need to add the directory to the `DIRECTORIES` variable.

Then move down to `SEPERATE` function and copy the for loop however changing where the copied subdirectory varibles are located and replacing them with the new directory name. *(case-sensitive)*


## Project technology

This project is running the following languages and tools:

* Bash

## Project commands

The commands to use dlorg follow as so;

```
./dlorg | Organizes files

./dlorg -v | Version of dlorg

./dlorg -h | Help section of dlorg
```

## What I learned

With this project I learned alot about how linux and mac differ and also work. I learned a bit of shell scripting and how to automate processes
that were rather time consuming before. This was alot of fun making and I am excited to do more shell scripting in the future.

## Links

- Project homepage: https://github.com/Dominicod/dlorg
- Repository: https://github.com/Dominicod/dlorg



## Licensing

The code in this project is licensed under MIT license.
