# C++

## Ninja build system

```
sudo apt-get install ninja-build
cmake -G Ninja ..
```

## ccache

Add to .bashrc
```
export PATH=/usr/lib/ccache:$Path
```

## ClangFormat

```
clang-format -i <file name>
```

###### ClangFormat in CLion
1. ClangFormatIJ plugin in 
      - settings 
        - plugins 
          - install
2. Define clang-format as an external tool
3. Add a keybinding for clang-format
      - settings 
        - keybinding 
          - clang
## Valgrind
[Valgrind](http://valgrind.org/) is an instrumentation framework for building dynamic analysis tools. There are Valgrind tools that can automatically detect many memory management and threading bugs, and profile your programs in detail. You can also use Valgrind to build new tools.
