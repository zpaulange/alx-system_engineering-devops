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


