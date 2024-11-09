Basic 'git' Commands                                                        - Description

git init —                                       - Navigate to your project directory and run this command to initialize a Git repository there.
git add filename.txt                             - to add a file from untraked area to staging area 
git add .                                        - to add all files from untracked area to staging area
git restore --staged filename.txt                - to remove a file from staging area to untracked area
git restore --staged .                           - to remove all file from staging area to untracked area
git commit -m                                    - to commit the modified changes to the repo with some commit message
git config --global user.email "xyz@abc.com"     - to set the git profile user email address
git config --global user.name "yourname"         - to set the git profile username
git config --global user.email                   - to get the user.email printed on terminal
git config --global user.name                    - to get the user.name printed on terminal 
git log                                          - to get the detailed history of commits(commit id, username and email of user that performed commit, time of commit)so far printed on the terminal
git checkout "commit id"                         - to get the modified code version of all files of that particular commit  
git checkout master                              - to go to the present working files (current version that you are working on presently)





Basic LINUX/Bash terminal commands               - Description  

echo "string"/ echo $anyVariableNameHere         - to print the given stirng or variable value on the terminal  
pwd                                              - to print the path of present working directory
cd dirName                                       - to change/enter the child directory 
cd ./ ../ ../../                                 - to close the present directory and go to parent directory ../../ close multiple directories at once
ls                                               - to print the names of all the files in the present directory
touch filename.txt                               - to create new file
mkdir dirName                                    - to create new directory
cat filename.txt                                 - to display the file contents on terminal             
vi filename.txt                                  - to open the file in vi(virtual interface) editor to edit the file 
vim filename.txt                                 - to open the file in vi(Virtual interface IMproved) editor to edit the file 
nano filename.txt                                - to open the file in nano editor to edit the file  
cp filename.txt folder3                          - to copy the file to other directory(folder3)
mv file.txt folder1                              - to move file to other directory
mv fillle.txt file.txt                           - to rename the file from filllle.txt to file.txt
rm filename.txt                                  - to delete the file 'filename.txt' permanently
rmdir                                            - to delete empty directories only
rm -r folder                                     - to delete the directory/folder permanently with all the files in it
alias                                            - to make a shortcut for larger and multiple lines of commands and represent them with a simple, single word




🚀 Taking my next step in backend development with essential Linux/Bash commands! 🖥️ The terminal is a powerful tool for backend developers, making tasks faster and more efficient. Using CLI really helps to work fast and streamline workflow! #nodejs #mern