# cmake

> Cross-platform build system generator.
> It generates Makefiles, Visual Studio projects or others, depending on the target system.

- Generate a Makefile and use it to compile a project in the same folder as the source:

`cmake && make`

- Generate a Makefile and use it to compile a project in a separate "build" folder (out-of-source build):

`mkdir -p {{build}} && cd {{build}} && cmake ../ && make`

- Run cmake in interactive mode (it will ask for each variable, instead of using defaults):

`cmake -i`