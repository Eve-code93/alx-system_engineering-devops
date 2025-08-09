#!/bin/bash
Your second line here
# alx-system_engineering-devops

cat > README.md << 'EOF'
# 0x03. Shell, init files, variables and expansions

This project contains Bash scripts for learning about shell initialization files, variables, expansions, shell arithmetic, and aliases.

## Scripts Description

### 0-alias
Creates an alias named `ls` with the value `rm *`.

### 1-hello_you
Prints `hello user`, where `user` is the current Linux user.

### 2-path
Adds `/action` to the end of the `PATH` environment variable.

### 3-paths
Counts the number of directories in the current `PATH`.

### 4-global_variables
Lists all environment variables.

### 5-local_variables
Lists all local variables, environment variables, and shell functions.

### 6-create_local_variable
Creates a new local variable `BEST` with the value `School`.

### 7-create_global_variable
Creates a new global variable `BEST` with the value `School`.

### 8-true_knowledge
Prints the sum of `128` and the value of the environment variable `TRUEKNOWLEDGE`.

### 9-divide_and_rule
Prints the result of the environment variable `POWER` divided by `DIVIDE`.

### 10-love_exponent_breath
Displays `BREATH` raised to the power of `LOVE`.

### 11-binary_to_decimal
Converts a binary number stored in `BINARY` to decimal.

### 12-combinations
Prints all possible combinations of two lowercase letters except `oo`.

### 13-print_float
Prints a number stored in `NUM` with two decimal places.
EOF
