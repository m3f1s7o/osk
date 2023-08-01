# Option Seeker (osk)
Bash tool to seek information about commands options. It searches the `man pages` or the `--help` output for the specified option.

## Install
```shell-session
$ cd
$ git clone https://github.com/m3f1s7o/osk
$ cd osk
$ chmod +x install
$ ./install
```

## Usage
```shell-session
$ osk "command -x"
```
## Options

### short `-s` (default)

Seeks the specified option using the `--help` or `-h` option of the argument command.

![image](https://github.com/m3f1s7o/osk/assets/65306021/a655be3f-4092-4b8e-964d-7afc69f55e38)

### long `-l`

Seeks the specified option in the `man page` of the argument command.

![image](https://github.com/m3f1s7o/osk/assets/65306021/90dc0e35-561a-42eb-abbc-4f23190e76be)
