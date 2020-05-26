PySoundFile
===========

`SoundFile <https://github.com/bastibe/SoundFile>`__ is an audio
library based on libsndfile, CFFI and NumPy. Full documentation is
available on http://soundfile.readthedocs.org/.

SoundFile can read and write sound files. File reading/writing is
supported through `libsndfile <http://www.mega-nerd.com/libsndfile/>`__,
which is a free, cross-platform, open-source (LGPL) library for reading
and writing many different sampled sound file formats that runs on many
platforms including Windows, OS X, and Unix. It is accessed through
`CFFI <http://cffi.readthedocs.org/>`__, which is a foreign function
interface for Python calling C code. CFFI is supported for CPython 2.6+,
3.x and PyPy 2.0+. SoundFile represents audio data as NumPy arrays.

| SoundFile is BSD licensed (BSD 3-Clause License).
| (c) 2013, Bastian Bechtold

This version is DEPRECATED. Please use SoundFile instead
--------------------------------------------------------

This repository **Py**SoundFile was renamed to *SoundFile* (without
the *Py*), as there is no need to tell Python programmers to use
Python. It is now an empty shell with no code, but a dependency on the
real version of SoundFile.

If your code is still using PySoundFile, please use SoundFile instead.
But don't worry, no code changes are required, as ``import soundfile``
works in both PySoundFile and SoundFile.
