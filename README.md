## Settings
Backing up custom alias and other bash profile settings, vimrc, and more because setting up new systems suck.

In the .bash_profile of the new machine, add this line at the top.
`. $HOME/PATH_TO_FUNCTIONS_FILE.sh`, where PATH_TO_FUNCTIONS_FILE is the file path of your custom functions.  
Then activate it using `source ~/.bash_profile`  

### Resources
https://apple.stackexchange.com/questions/242190/moving-bash-profile-to-dropbox/242191
