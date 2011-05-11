#Coda from command line

###What
A very simple ruby script to launch coda from command line just like you do with textmate

###How
    coda readme.txt
    coda *.rb
    coda jquery.js site.js
    coda directory_name/

###Where
Make the script executable and put it in /usr/local/bin/  
    chmod +x coda
    mv coda /usr/local/bin/coda

###Issues
This script guess that your Coda.app is in /Applications/Coda.app  
if is not just set the environment variable $CODAPATH with your current Coda.app location  
    export CODEPATH=/path/to/Coda.app

##Credits
This script is released as it is, please use it at your own risk.