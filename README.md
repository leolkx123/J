# `J`
## Compile and execute Java "scripts" in one go!

Java feels a bit clunky at times. `J` is here to fix that.

`J` gives Java a *scripting* feel. `J` speeds up the development process and saves you the trouble of running...

```sh
$ javac Sudoku.java
$ java Sudoku
```

...each time you modify the source code.

`J` was inspired by [`c`](https://github.com/ryanmjacobs/c), a wonderful project that allows you to "compile and execute C 'scripts' in one go!"


## Getting Started
After the [super painless drag-and-drop installation](#installation), you can [start using `J`](#usage) right away.

## Usage
### Compile and run Java source file
```sh
$ j Sudoku.java
```

Where `Sudoku.java` is the Java source file.

### Compile and run Java source file *with arguments*
```sh
$ j Sudoku.java Jack Jill
```

Where `Sudoku.java` is the Java source file. `Jack` and `Jill` are command line arguments (accessed with `args[0]` and `args[1]` in the main method of Sudoku.java).

## Installation
After downloading the Bash script, simply copy it over to your `$PATH` and you're good to go.
```sh
$ wget https://github.com/qw3rtman/j/releases/download/v0.1.0/j
$ mv j /usr/local/bin
```

`J` (obviously) depends on Java (`java` and `javac`). Other than that, `J` has no dependencies!

## Updating
Simply follow the above steps and swap out the old Bash script with the new one!

## Contributing
Contributions are always welcome.

Find something interesting in the TODO below, fork our code, create a new branch, and send us a pull request.

There are only two rules: avoid [code smells](http://blog.codinghorror.com/code-smells/) and abide by the syntax-formatting of the existing code.

## TODO
* **support for compiler options**

## FAQs

## Core Team
### Nimit Kalra
* <nimit@nimitkalra.com>
* <http://nimitkalra.com>
* <https://github.com/qw3rtman>
* <https://twitter.com/qw3rtman>
