codeship-opencv
===============

OpenCV compiled to run on codeship. Used only to get python support.

To install
==========

```bash
cd ~
git clone https://github.com/ianyh/codeship-opencv
tar xzvf codeship-opencv/opencv-lib.tar.gz
export PYTHONPATH="$HOME/opencv-lib/lib/python2.7/site-packages/"
export LD_LIBRARY_PATH="/usr/lib/atlas-base/atlas"
cd clone
```
