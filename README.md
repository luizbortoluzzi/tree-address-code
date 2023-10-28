# TREE ADDRESS CODE GENERATOR

This project is a tree address code generator, implemented in C++.

## Project Structure

- `ast.cpp` and `ast.h`: Implementation and definitions related to the Abstract Syntax Tree (AST).
- `checker.cpp` and `checker.h`: Features for verification and validation.
- `compiler.cpp`: Main entry point for the compiler.
- `error.cpp` and `error.h`: Error handling and error messages.
- `gen.cpp` and `gen.h`: Code generation functionalities.
- `lexer.cpp` and `lexer.h`: Lexical analysis and tokenization.
- `parser.cpp` and `parser.h`: Parsing and AST construction.
- `symtable.cpp` and `symtable.h`: Symbol table and scope management.

## Setup and Compilation

This project uses CMake for build system generation. To compile the project:

1. Create a directory for the build (e.g., `build`):

```sh
mkdir build
cd build
```

2. Generate the build files using CMake:

```sh
cmake ..
```

3. Compile the project:

```sh
make
```

## Mock Programs

The mock programs are located in the `mocks` directory and can be executed after the project has been compiled.

```sh
cd build
./compiler ./../mocks/test_5.cpp
```

## Contribution

If you wish to contribute to this project, please follow the contribution guidelines and submit your pull request.

## License

[Insert license information here, if applicable]



