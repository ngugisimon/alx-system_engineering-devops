alias ls='rm *' -- script that creates an alias

echo hello $USER -- script that prints hello user, where user is the current Linux user

export PATH=$PATH:/action -- Add /action to the PATH. /action should be the last directory the shell looks

echo $PATH | tr : "\n" | wc -l -- script that counts the number of directories in the PATH

printenv | less -- script that lists environment variables

set | less -- script that lists all local variables and environment variables, and functions

export BETTY=Holberton -- script that creates a new local variable

export BEST=School -- script that creates a new global variable

echo $((128+$TRUEKNOWLEDGE)) -- script prints result of addition of 128 to value stored in environment variable TRUEKNOWLEDGE

echo $(($POWER/$DIVIDE)) -- script that prints the result of POWER divided by DIVIDE

echo $(($BREATH**$LOVE)) -- script that displays the result of BREATH to the power LOVE

echo $((2#$BINARY)) -- script that converts a number from base 2 to base 10

echo {a..z}{a..z} | tr " " "\n" | grep -v "oo" -- script that prints all possible combinations of two letters, except oo

printf "%.2f\n" $NUM -- script that prints a number with two decimal places
