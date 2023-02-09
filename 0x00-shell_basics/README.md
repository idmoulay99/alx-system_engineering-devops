pwd : prints the absolute path name of the current working directory.
ls : Display the contents list of your current directory.
cd /root : script that changes the working directory to the user’s home directory.
ls -l : Display current directory contents in a long format.
ls -la : Display current directory contents, including hidden files (starting with .). Use the long format.
ls -na : Display current directory contents.Long format, with user and group IDs displayed numerically, And hidden files (starting with .)
mkdir /tmp/my_first_directory : script that creates a directory named my_first_directory in the /tmp/ directory.
mv /tmp/betty /tmp/my_first_directory/ : Move the file betty from /tmp/ to /tmp/my_first_directory.
rm /tmp/my_first_directory/betty : Delete the file betty. The file betty is in /tmp/my_first_directory.
rm -r /tmp/my_first_directory : Delete the directory my_first_directory that is in the /tmp directory.
cd - : script that changes the working directory to the previous one.
ls -la . .. /boot : script that lists all files  in the current directory and the parent of the working directory and the /boot directory
file /tmp/iamafile : script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory
ln -s /bin/ls ./__ls__ : Create a symbolic link to /bin/ls, named __ls__
cp -ur *.html ../ : script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
mv [A-Z]* /tmp/u : script that moves all files beginning with an uppercase letter to the directory /tmp/u
rm *~ : script that deletes all files in the current working directory that end with the character ~.
mkdir -p welcome/to/school : script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
ls -map : lists all the files and directories of the current directory, separated by commas (,). Directory names should end with a slash (/)\nFiles and directories starting with a dot (.) should be listed\nThe listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning\nOnly digits and letters are used to sort; Digits should come first\nYou can assume that all the files we will test with will have at least one letter or one digit\nThe listing should end with a new line
