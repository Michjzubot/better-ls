# better-ls

A small tree-style `ls` for the terminal with icons, colors, depth control, sorting, and filtering.

## Features

- Tree output with configurable recursion depth
- Long view with permissions, size, and modified time
- Sorting by name, size, time, or type
- Filters for files, directories, glob ignores, and `.gitignore`
- Compact mode, summaries, colors, and switchable icons

## Requirements

- Python 3.7+

## Install to `/bin`

Install the script system-wide:

```bash
sudo install -m 755 better-ls /bin/better-ls
```

Then run it with:

```bash
/bin/better-ls
```

## Replace `ls` in `.bashrc`

Add this alias to your `~/.bashrc`:

```bash
alias ls='/bin/better-ls'
```

Apply it in the current shell:

```bash
source ~/.bashrc
```

## Usage

```bash
./better-ls
./better-ls 2
./better-ls /path/to/folder 3 --long
./better-ls --sort size --summary
./better-ls --ignore '*.log' --gitignore
./better-ls --compact --max 20
./better-ls --icons off --color always
```

Run `./better-ls --help` for the full option list.

## License

MIT
