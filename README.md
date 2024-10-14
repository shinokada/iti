# ITI (Image to Image)

A simple bash script using magick to convert png, jpg, and jpeg image to the image so that it shows the thumbnail in the macOS finder.

The script will process all PNG, JPG, and JPEG files in the ~/Documents/iti directory.

## Features

- Renames image files to lowercase with hyphens instead of spaces
- Processes PNG, JPG, and JPEG files
- Moves original files to an 'original' subdirectory
- Uses ImageMagick to process images

## Prerequisites

- Bash shell (Unix-like operating system or Git Bash for Windows)
- ImageMagick installed on your system

## Installation

Install [awesome package manager](https://github.com/shinokada/awesome).

Then install `iti`.

```
awesome install iti
```

Create a `document/iti` directory and put your images in it.

Then run `iti` on your terminal.

```
iti
```

## Notes

- Ensure you have necessary permissions to read, write, and execute files in the target directory.
- This script will overwrite existing files with the same name in the parent directory after processing.

## Troubleshooting
If you encounter any issues:

- Ensure ImageMagick is installed and accessible from the command line.
- Check that you have the necessary permissions in the target directory.
- Verify that there are image files of the specified types in the directory.

For any other issues or feature requests, please open an issue in the project repository.