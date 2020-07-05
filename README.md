# img_dir_walk
usage: img_dir_walk.py [-h] -i DIR -o STR [-v]

Determines file paths of child directories that contain medical images, and
their corresponding image types from some parent directory. Output files
consists of lists written to text files with '.dir_list.txt' and
'.type_list.txt' appended to them.

optional arguments:
  -h, --help            show this help message and exit

Required arguments:
  -i DIR, --image-dir DIR
                        Parent image directory.
  -o STR, --output STR  Output files' prefix.

Optional arguments:
  -v, --verbose         Enables verbose output to screen.
