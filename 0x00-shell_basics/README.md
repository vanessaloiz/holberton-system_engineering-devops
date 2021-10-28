Task for the projects 0x00-shellbasics

Exercise 0: Write a script that prints the absolute
path name of the current working directory: pwd.

Exercise 1: Display the contents list of your current directory: ls.

Exercise 2: Write a script that changes the working 
directory to the user’s home directory: cd.

Exercise 3: Display current directory contents in a long format: ls -l.

Exercise 4: Display current directory contents, including hidden files
 (starting with .). Use the long format: ls -la.

 Exercise 5: Display current directory contents: ls -la -n.

 Exercise 6: Create a script that creates a directory named 
 my_first_directory in the /tmp/ directory: mkdir /tmp/my_first_directory.

 Exercise 7: Move the file betty from /tmp/ to /tmp/my_first_directory:
 mv /tmp/betty /tmp/my_first_directory/betty.

 Exercise 8: The file betty is in /tmp/my_first_directory: rm /tmp/my_first_directory/betty.

 Exercise 9: Delete the directory my_first_directory that is in the /tmp directory:
 rmdir /tmp/my_first_directory.

Exercise 10: Write a script that changes the working directory to the previous one: cd -.

Exercise 11: Write a script that lists all files (even ones with names beginning 
with a period character, which are normally hidden) in the current 
directory and the parent of the working directory and the /boot directory 
(in this order), in long format: ls -la . .. /boot.

Exercise 12: Write a script that prints the type of the file named iamafile
The file iamafile will be in the /tmp directory: file /tmp/iamafile.

Exercise 13: Create a symbolic link to /bin/ls, named __ls__.
The symbolic link should be created in the current working directory:
ln -s /bin/ls __ls__.

Exercise 14: Create a script that copies all the HTML files from
the current working directory: cp -R *.html . ..

Exercise 15: Create a script that moves all files beginning
with an uppercase letter to the directory /tmp/u:
mv [[:upper:]]* /tmp/u.

Exercise 16: Create a script that deletes all files in the current working 
directory that end with the character ~: rm *~.

Exercise 17: Create a script that creates the directories welcome/, 
welcome/to/ and welcome/to/school in the current directory:
mkdir -p welcome/to/school.

Exercise 18: Write a command that lists all the files and directories
of the current directory, separated by commas (,).
ls -pam.

Exercise 19: Create a magic file school.mgc that can be used with the 
command file to detect School data files.School data files always 
contain the string SCHOOL at offset 0:
0 string SCHOOL School
data !:mime School
