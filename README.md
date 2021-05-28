# Clox
Implementing clox from http://www.craftinginterpreters.com/

Clox is a bytecode compiler and virtual machine for a custom language lox.

### Compile
Requires `gcc`.
```
./build.sh
```

### Run
##### REPL
```
./clox
```

##### Script
```
./clox programs/toyrobot.lox
```

### Fun
Try uncommenting various `#define DEBUG_*` lines from `common.h` to see more detail about compilation or execution.
