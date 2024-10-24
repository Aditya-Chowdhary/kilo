A terminal text editor built in C with the help of [Build Your Own Text Editor by Snaptoken](https://viewsourcecode.org/snaptoken/kilo/)

### How to Run
This has been developed on WSL and will work on Linux or MacOS. Will not work on Windows.

1. Clone the repository
2. Run `make`
3. Alternatively, compile the `kilo.c` file with any C compiler of your choice.
4. Run `./kilo` to open a new file in the current directory
5. Run `./kilo [filename]` to open the filename.

### Features:   
- Standard text operations - adding/removing text/lines
- Incremental search with arrows keys to go up/down results
- Basic syntax highlighting of numbers, comments, keywords, strings in C
- Status Bar with file name, number of lines, file type
- Prompt Bar for search, save, etc.
- Ctrl-S to Save, Ctrl-S on a new file to save as [filename]
- Ctrl-F to search
- Ctrl-Q to quit. Requires multiple presses of Ctrl-Q to quit an unsaved buffer.