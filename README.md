<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [bash_cookbook](#bash_cookbook)
  - [String Functions](#string-functions)
    - [Check if String starts with](#check-if-string-starts-with)
    - [Check if String ends with](#check-if-string-ends-with)
  - [Regex](#regex)
    - [Replace line in file](#replace-line-in-file)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# bash_cookbook
Just a cookbook of common bash scripting functions


## String Functions

### Check if String starts with 

```
[[ $a == z* ]]   # True if $a starts with a "z" (wildcard matching).
[[ $a == "z*" ]] # True if $a is equal to z* (literal matching).
```

### Check if String ends with

```
[[ "$STRING == *ing ]]  #True if $STRING ends with "ing"
[[ "$STRING == *ing ]]  #False if $STRING does not ends with "ing"
```

## Regex 

### Replace line in file

sntes
