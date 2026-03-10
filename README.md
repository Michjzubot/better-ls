# better-ls

A small tree-style `ls` for the terminal with icons, colors, depth control, sorting, and filtering.

## Features

- Tree output with configurable recursion depth
- Long view with size, modified time, and optional permissions
- Sorting by name, size, time, or type
- Filters for files, directories, glob ignores, and `.gitignore`
- Compact mode, summaries, colors, and switchable icons

## Requirements

- Python 3.7+

## Usage

```bash
./better-ls
./better-ls 2
./better-ls /path/to/folder 3 --long --permissions
./better-ls --sort size --summary
./better-ls --ignore '*.log' --gitignore
./better-ls --compact --max 20
./better-ls --icons off --color always
```

Run `./better-ls --help` for the full option list.

## License

MIT
