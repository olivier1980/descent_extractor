# Descent-Extractor
Python tool to extract assets from Descent game and convert them, based on the Node.js extraction tool found here: https://github.com/Daivuk/Descent-Extractor 

Copy **descent.pig** and **descent.hog** files from your Descent installation into the `input/` directory.

Extracted assets in their Raw data will be inside `output/` directory, if option `output_raw` is enabled.

Converted PCX assets into PNGs will be inside `converted/` directory.

Use the flags in extractor.py to determine what will be converted.