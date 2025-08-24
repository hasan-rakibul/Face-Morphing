Fork of [Face Morphing](https://github.com/Azmarie/Face-Morphing)
===================

Please checkout the [README of original Face Morphing](https://github.com/Azmarie/Face-Morphing/blob/master/README.md) project regarding the details of the original project. Thanks to the original authors for their work.

## Improvements in this fork
- Updated `requirements.txt` to support latest packages. Tested with `Python 3.13.2`.
- Made the save as video optional (with the flag `save_as_video`) since it didn't work in my environment and also I needed raw images.
- Added saving as raw image frames, with the flag `save_as_img`.
- Added `do_morphing.sh` to simplify testing on a new image pair.
- Improved sharpness of output images.
