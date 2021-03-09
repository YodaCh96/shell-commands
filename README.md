# UNIX-CLI

In the terminal, first you see `$`. This is called a **shell prompt**. It appears when the terminal is ready to accept a command.

The **command line** is a text interface for the computer's operating system. To access the command line, we use the **terminal**.

A **filesystem** organizes a computer's files and directories into a tree structure. It starts with the root directory. Each parent directory can contain more child directories and files.

- `pwd` outputs the name of the current working directory.
- `ls` lists all files and directories in the working directory.
- `cd` switches you into the directory you specify.
- `cd ..` move up one folder.
- `mkdir` creates a new directory in the working directory.
- `touch` creates a new file inside the working directory.
- `rm –r` removes directories and their contents recursively.
- `rm` removes files.
- `cp` copies files.
- `mv` moves and renames files.
- `ls -a` lists all contents of a directory, including hidden files and directories.
- `ls -l` lists all contents in long format.
- `ls -t` orders files and directories by the time they were last modified.
- `sort` sorts lines of text alphabetically.
- `uniq` filters duplicate, adjacent lines of text.
- `grep` searches for a text pattern and outputs it.
- `sed` searches for a text pattern, modifies it, and outputs it.
- `export VARIABLE="Value"` sets and exports an environment variable.
- `USER` is the name of the current user.
- `PS1` is the command prompt.
- `HOME` is the home directory. It is usually not customized.
- `PATH` returns a colon separated list of file paths. It is customized in advanced cases.
- `env` returns a list of environment variables.

**Wildcards** are useful for selecting groups of files and directories.

- `>` redirects standard output of a command to a file, overwriting previous content.
- `>>` redirects standard output of a command to a file, appending new content to old content.
- `<` redirects standard input to a command.
- `|` redirects standard output of a command to another command.

## Contributing

This is a personal learning project for me. Please feel free to fork this repo. Pull request to submit more programs.

## Feedback

If you find any bug or have any suggestion, please do file issues. I am graceful for any feedback and will do my best to improve this package.

## License

[MIT](LICENSE) © 2020 Ioannis Christodoulakis
