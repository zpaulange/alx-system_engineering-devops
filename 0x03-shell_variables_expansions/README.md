Shell, init files, variables and expansions

#create an alias
alias ls="rm *"

#print the current user
echo $USER

#add path
PATH="$PATH:/action"

#echo created pash
echo $PATH | tr ':' '\n' | wc -l

#global variable
printenv

#lists all local variables and environment variables, and functions
set:x

#creates a new local variable
BEST=School

#create a new global variable
export BEST=School

#prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line
echo $(($TRUEKNOWLEDGE+128))

#divide and rule
echo $(($POWER/$DIVIDE))

#displays the result of BREATH to the power LOVE
echo $(($BREATH**LOVE))

