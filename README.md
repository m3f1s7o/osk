# Option Seeker (osk)
Bash tool to seek information about commands options. It searches the `man pages` or the `--help` output for the specified option.

## Install
The installation will put the `osk` script on the `~/.local/bin/` directory.

```shell-session
$ cd
$ git clone https://github.com/m3f1s7o/osk
$ cd osk
$ chmod +x install
$ ./install
```

## Usage
```shell-session
$ osk [command] -[option1] -[option2] -[optionX]
```
> The options must be **separated**. The script is able to seek information for long or short options (`-o` or `--option`).

## Options

### short `-s` (default)

Seeks the specified option using the `--help` or `-h` option of the argument command.

![image](https://github.com/m3f1s7o/osk/assets/65306021/52e105f3-7837-48cc-a68d-feb1bc338a25)

### long `-l`

Seeks the specified option using the `man page` of the argument command.

![image](https://github.com/m3f1s7o/osk/assets/65306021/d1d95a69-b3f9-4f34-bb69-edae90dd44f7)

---
# To add

- [x] If no osk option specified, first search help, if not found, go to man pages.

# Bugs

- [ ] Option is listed besides another (`osk -l cp -r` -> `-R, -r, --recursive`)
- [ ] If just `-` is introduced as option, all options are printed (`osk -l ls - l`)
- [ ] `find` command options

