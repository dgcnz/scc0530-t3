# SCC0530: T3 - Pathfinder

## 

## Usage

```sh
# Compile project
make all 

# This will produce an executable called pathfinder
# Usage: pathfinder <filename> <algorithm> 
$ ./pathfinder --help
Available parameters:

  -h    --help

   This parameter is optional. The default value is ''.

  -a    --algorithm     (required)
   Pathfinding algorithm.

  -i    --input
   Input file.
   This parameter is optional. The default value is ''.

  -o    --output
   Output file.
   This parameter is optional. The default value is ''.

  -g    --generate
   Generate maze with {rows}, {cols}, (optional){seed}.
   This parameter is optional. The default value is '[ ]'.

  -d    --dist
   Distance metric. Use manhattan or euclidean.
   This parameter is optional. The default value is 'manhattan'.

  -v    --verbose
   Prints output to stdout.
   This parameter is optional. The default value is '0'.

  -e    --export
   Exports input maze to file.
   This parameter is optional. The default value is ''.
```

Note
- One has two options to specify an input maze: through a file and by specifying valid arguments to the Maze generator using the `-g` flag.
- If one wants to save the maze generated by the Maze Generator, use the `-e` flag.
- If one wants the input and output maze printed to stdout, use the `-v` flag.
