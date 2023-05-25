# Batch\_Scripts
A variety of scripts focused on batch file processing.


## batch-rename.sh
A simple script that will rename files of a specific filetype numerically, with whatever filename you want preceding.

    $ ./batch-rename -o { PUT OUTPUT FILE NAME BEFORE THE NUMERIC VALUE HERE } -e { FILE EXTENSION OF FILES YOU WANT RENAMED }

## batch-rename-numeric.sh
A simple script that will rename files/folders numerically with no file extensions. Will rename all files outside of itself to a numeric value in read in order.

    $ ./batch-rename-numeric.sh

## batch-ffmpeg-crop.sh
A script that can be used to iterate through files in a directory and crop them to the specified aspect ratio.

    $ ./batch-ffmpeg-crop.sh -o { PUT OUTPUT FILE NAME BEFORE THE NUMERIC VALUE HERE } -w { DESIRED WIDTH RATIO } -h { DESIRED HEIGHT RATIO }
