# About 
Convert RTF (Rich Text Format) format file to plain text file

# Requirement
```
python >2.7
Python packages:
re
glob
os
argparse
sys
```
# Input file
RTF format file (see "example.rtf")

# Quick start
`python rtf2txt.py -i example.rtf`

# Usage and help
```
$ python rtf2txt.py -h
usage: rtf2txt.py [-h] -i INPUT [-d OUTDIR] [-o OUTPUT]

convert RTF format file to plain text file

optional arguments:
  -h, --help            show this help message and exit
  -i INPUT, --input INPUT
                        input your RTF format file
  -d OUTDIR, --outdir OUTDIR
                        the path to the output folder(default: ./ )
  -o OUTPUT, --output OUTPUT
                        text output file name (default: text.txt)

before running, please install required python packages
```
