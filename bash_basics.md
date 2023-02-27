#Linux/Bash commands:
ls - Lists files in current directory. Flags; -a - shows hidden files. -l - shows more detailed info

cd - Changes directory using the given path. ~ for the home directory. / for the root directory. Give an argument starting with / for relative path e.g. cd /this_dir/that_dir
.. to move one level up ../.. to move two levels up etc.

mkdir - Makes a directory in the current location. Provide the name of the new directory as an argument. Usage: mkdir new_dir_name

nano - Brings up a text editor in bash. Can use nano filename to create a new file. Usage: nano new_filename

cat - Shows the top line of a file. Usage: cat filename

cp - Makes a copy of a file. Useage: cp original_file name_of_new_file

mv - Moves a file to a target directory (cut and paste). Useage: mv filename target_directory

rm - Deletes a specified file. To delete a directory, use the flags -rf. Must be very careful with these flags. -r - deletes the target directory and any directories in the target.
-f override/forces target to be deleted. If a target directory is not provided, the command will delete the current working directory and all its contents. Usage rm filename, rm -rf dir_name

pwd - Returns the current working directory.

touch - Creates a new file without needing to open it. Usage: touch newfilename