# simple shell (hsh)

simple shell project it's a command-line interpreter, building in C language  

## Dowload

Clone the [repository](https://github.com/exploitpnk/simple_shell.git)

```bash
git clone https://github.com/exploitpnk/simple_shell.git
```

## Compile
Compile all .c files
```bash
gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
```
Now you're ready to use our simple shell.

## Usage
The simple shell (hsh) works like '/bin/sh', the program reads the typed commands and use the execve function to open binaries and pass arguments to it.

## Examples

List files using agruments
```
$ ls -l /usr
```

Print current working directory
```
$ pwd
```


## Authors

Gabriel Montaño, Juan Camilo Esquivel



