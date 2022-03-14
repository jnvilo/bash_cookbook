<!-- START doctoc -->
<!-- END doctoc -->

# bash_cookbook
Just a cookbook of common bash scripting functions


## String Functions

### Check if String starts with 

[[ $a == z* ]]   # True if $a starts with a "z" (wildcard matching).
[[ $a == "z*" ]] # True if $a is equal to z* (literal matching).

### Check if String ends with

[[ "$STRING == *ing ]]  #True if $STRING ends with "ing"
[[ "$STRING == *ing ]]  #False if $STRING does not ends with "ing"

