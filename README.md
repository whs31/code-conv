# Convention

# [Code Style](code-style/index.md)

## Cmake console commands

- cmake -D CMAKE_BUILD_TYPE [DEBUG | RELEASE | RELWITHDEBINFO | MINSIZEREL] -D CMAKE_C_COMPILER=[PATH TO YOU C COMPILER] -D CMAKE_C_COMPILER=[PATH TO YOU CXX COMPILER] -D BUILD-SHARED-LIBS=ON -S [PATH TO Cmake.txt FOLDER] -B [PATH TO BUILD FOLDER]
- cmake --build [PATH TO BUILD FOLDER] --config [DEBUG | RELEASE | RELWITHDEBINFO | MINSIZEREL] --parallel
- cmake --install [PATH TO BUILD FOLDER] --prefix [TARGET PREFIX]

[more information...](./UsefullVariables.md)