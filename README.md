# data210_git_basics

Hello this change was made on my local machine.
Hello this change was mad on github.

Linux/Bash commands:
ls - lists files in current directory. Flags; -a - shows hidden files. -l - shows more detailed info

cd - changes directory using the given path. ~ for the home directory. / for the root directory. Give an argument starting with / for relative path e.g. /this_dir/that_dir
.. to move one level up ../.. to move two levels up etc.

mkdir - makes a directory in the current location. Provide the name of the new directory as an argument.

nano - Brings up a text editor in bash. can use nano filename to create a new file.

cat - shows the top line of a file.

cp - makes a copy of a file. useage: cp original_file name_of_new_file

mv - Moves a file to a target directory (cut and paste). useage: mv filename target_directory

rm - deletes a specified file. To delete a directory,  use the flags -rf. Must be very careful with these flags. -r - deletes the target directory and any directories in the target.
-f override/ forces target to be deleted. If a target directory is not provided, the command will delete the current working directory and all its contents.

pwd - returns the current working directory.

touch - creates a new file without needing to open it. touch newfilename

Git Commands:

status - shows status of files in current directory compared to the repository. Files in red have been changed and these changes have not been added. Files in green have been changed
and these changes have been added.

add - Adds the changes in the given file(s) to the commit. can use the argument . to select all files.

commit - commits any changes made to the local repository. Flags -m - adds a message to the commit

push - pushes any local commits from your local repository to the central repository. 
