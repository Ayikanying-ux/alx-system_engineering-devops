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

* export BEST="School"

```creates a global variable BEST and sets the value to School```

* echo $((128+TRUEKNOWLEDGE))

```prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line```

* echo $((POWER/DIVIDE))

```prints the result of POWER divided by DIVIDE, followed by a new line```

* echo $((BREATH**LOVE))

```displays the result of BREATH to the power LOVE```

* echo $((2#$BINARY))

```converts a number from base 2 to base 10```

* echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo"

```prints all possible combinations of two letters, except oo```

* printf '%.2f\n' $NUM

```prints a number with two decimal places, followed by a new line```

* printf '%x\n' $DECIMAL

```converts a number from base 10 to base 16```
