# Simple-Image-Converter

A simple python image converter

## Installation:

Install pillow using pip.

```sh
pip install pillow
```

## Usage:

```sh
Usage:
python resizer.py [input file name] [operation] [argument]

Operations:
-f : Format image(png to jpg and vice versa)
Example 1: python resizer.py image.jpeg -f png
Example 2: python resizer.py image.png -f jpeg

-r : Resize image
Example 1: python resizer.py image.jpeg -r 200x200
Example 2: python resizer.py image.png -r 250x200
```

## Examples

1. Image format conversion

```sh
python resizer.py image.jpeg -f png
```

2. Image resizing

```sh
python resizer.py image.jpeg -r 200x200
```

## Libraries used:

- [Pillow](https://python-pillow.org/)
