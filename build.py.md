# build.py

build.py is a simple script which can install dependencies or compile the script with pyinstaller/cxfreeze.

- `--deps-build`: Install required dependencies to start compiling or running the script.
- `--deps`: Install required dependencies to start running the script.
- `--pyinstaller`: Compile with `pyinstaller`. Stores in `pyinstaller` directory.
- `--cxfreeze`: Compile with `cxfreeze`. Stores in `cxfreeze` directory.
- `-r`, `--remove`: Cleans up build directories.
