# cvutils
This repository contains useful utilities to ease the task of creating computer vision and image processing projects. A number of command line tool have also been added to make the project useful for general use.

# REQUIREMENTS
1. `cv2`
2. `os`
3. `matplotlib`
4. `argparse`

## INSTALLATION

1. From source
```bash
git clone https://github.com/bikz05/cvutils.git
python install setup.py
```

2. From PyPI
```
pip install cvutils

```
You might need root access to install the package globally on Linux. Use the `sudo` prefix to solve this problem.

## Command line tools

1. Resizing an image
To resize an image use the command-line tool `cvutils-resize`.
```bash
cvutils -i <path to image> -w <required width> -ht <required height>
```
The resuting image is saved in the same directory as the input image with the suffix -resized added before the extension.
Height (-ht) is optional and is automatically calculated if width is set to zero.
