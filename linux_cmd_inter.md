# Linux Commands Intermediate - Level

## Exploring the System

| Command  | Description                                                          | Example                                                                         |
| -------- | -------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| `file`   | Determin file type.                                                  | `file picture.jpg` results : `picture.jpg: JPEG image date, JFIF standard 1.01` |
| less     | easy viewing of long text document                                   | `less /etc/passwd` use pgup/pgdwn or return                                     |
| `ln`     | create link between files like shortcuts in windows                  | `ln file-name file-linkname-hard` ; `ln -s filename file-symbolic-link-name`    |
| type     | Display information about command type                               | `type ls` results: `ls is aliased to ls --color=auto`                           |
| `which`  | locate a command and its path or which version the terminal is using | `which ls` [!NOTE] `which` works only for executables not builtins or aliases   |
| `whatis` | one-line from manual (man) page                                      | `whatis ls `                                                                    |
