# 0x03. Shell, init files, variables and expansions

* alias ls="rm *" 

```Creating a new command for ls. Instead of using ls rm * will used in place of ls```

* echo "hello $USER"

```Prints hello user on the terminal```

* export PATH=$PATH:/action

```Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program```

* find $PATH -mindepth 1 -type d | wc -l

```Create a script that counts the number of directories in the PATH```

* printenv

```lists environment variables```

* set 

```lists all local variables and environment variables, and functions```

* BEST="School"

```creates a variable BEST adn sets the value to School```
