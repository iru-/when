# when
`When` is a command-line tool that watches a file or directory for modification
and executes a command in response to that.

It currently runs on Linux over x86-64.

# Usage
`When` requires a `nop` [1] binary to found in $PATH and that `nop` can find
clib. This can be achieved by
```
% export NOPLIBS=/path/to/nop/libs
```

To execute a command in response to a change in a file, do
```
% when /path/to/file command
```

# References
[1] https://github.com/iru-/nopforth

