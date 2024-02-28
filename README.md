# matplotlib
Matplotlib, conceived by John D. Hunter, stands as a low-level graph plotting library within the Python ecosystem, functioning as a robust visualization utility.

## Install an Official Release

Matplotlib releases are available as wheel packages for macOS, Windows, and Linux on PyPI. Install it using pip:

```bash
python -m pip install -U pip
python -m pip install -U matplotlib
```

If this command results in Matplotlib being compiled from source and there's trouble with the compilation, you can add --prefer-binary to select the newest version of Matplotlib for which there is a precompiled wheel for your OS and Python.

### Linux Package Manager

If you are using the Python version that comes with your Linux distribution, you can install Matplotlib via your package manager. Use the following commands based on your distribution:

Debian / Ubuntu:
```bash
sudo apt-get install python3-matplotlib
```

Fedora:
```bash
sudo dnf install python3-matplotlib
```

Red Hat:
```bash
sudo yum install python3-matplotlib
```

Arch:
```bash
sudo pacman -S python-matplotlib
```

Make sure to replace python3-matplotlib or python-matplotlib with the appropriate package name if there are any variations based on the distribution.

## Animations using Matplotlib

Based on its plotting functionality, Matplotlib also provides an interface to generate animations using the `animation` module. An animation is a sequence of frames where each frame corresponds to a plot on a Figure. This tutorial covers a general guideline on how to create such animations and the different options available.

```bash
import matplotlib.pyplot as plt
import numpy as np
import matplotlib.animation as animation
```