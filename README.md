# wtcli
web tool command line interface 

Make sure you have updated your $PATH inside your .bash_profile or bashrc 
# export PATH=$PATH:/Users/yourusername/scripts/wtcli

Simply start the program by typing wtcli to your mac terminal:

# wtcli

once inside you will see 4 options. The Create, Develop, and Deploy functions are not fully finished.

Type vvs and enter to begin running the vvs interpreter.

vvs interprets and runs custom bash scripts defined in the vvs folder.
# type the name of the script followed by arguments if necessary, seperated by spaces. Shown Below.

to see your environment variables:
# env

to set environment variables:
# envset 'key' 'value'
# envset workingfile index.html
# envset collections bootstrap
# envset match <body>

to get a specific environment variable
# envget match
# envget keyname

to add a saved html/javascript/any predetermined template to the workingfile use the add command:

# add header
# add footer
# add templatename

!! make sure your environment variables are set correctly !!

Here's what happens:

1. the command will look for the collection you set in the environment and then 
2. find the templatename inside that collection.
3. It will append that template to the matching pattern in the environment variable

There is a way to create templates if you exit back to the original menu and type:

# Create
# temp

