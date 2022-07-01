alias ls='rm *' -- script that creates an alias

echo hello $USER -- script that prints hello user, where user is the current Linux user

export PATH=$PATH:/action -- Add /action to the PATH. /action should be the last directory the shell looks

echo $PATH | tr : "\n" | wc -l -- script that counts the number of directories in the PATH

printenv | less -- script that lists environment variables

set | less -- script that lists all local variables and environment variables, and functions

export BETTY=Holberton -- script that creates a new local variable

export BEST=School -- script that creates a new global variable

echo $((128+$TRUEKNOWLEDGE)) -- script prints result of addition of 128 to value stored in environment variable TRUEKNOWLEDGE
