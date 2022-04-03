# Steganography LSB

Hide messages as well as images withing a PNG image and be able to retrieve them.

Python 3+ is required for the program to run.

Argument options: 
* -e Hide a string in an image
* -d Retrieve a string from an image 
* -i Hide an image in another image 
* -u Retrieve an image from another image

> *Only images RGBA pngs are supported*

## Usage

```bash
steg.py

Usage:
  python steg.py -e <file>
  python steg.py -d <file>
```
> *Make sure to include the extension along with the filename*

