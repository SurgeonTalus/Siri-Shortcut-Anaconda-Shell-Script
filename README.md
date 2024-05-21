# Siri-Shortcut-Anaconda-Shell-Script
Run shell scripts in Siri shortcut with all python anaconda packages enabled

I am using anaconda so this is what I do to make my anaconda library available for the shell scripts in shortcuts and Automator:

I paste the code under into the shell script window, change the name to my home folder name then I add my code and python scripts will run like a charm!

/Users/HOMEFOLDER/anaconda3/bin/python <<EOF import sys 

print("RUN any ANACONA SCRIPT HERE!")

EOF
