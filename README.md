# Quick and Dirty audio degrader

Simple GUI program, that allows degrading (downsampling and bit decimation) of audio samples. Coded in Python, and compatible with MacOS, Windows and Linux.

<details><summary>Screenshots of the main window on different OS's</summary><blockquote>
  <details><summary>Mac OS</summary>
    <p align="center">
    <img src=".readme_img/ss%20mac.png">
    </p>
  </details>
  <details><summary>Linux</summary>
    <p align="center">
    <img src=".readme_img/ss%20linux.png">
    </p>
  </details>
  <details><summary>Windows</summary>
    <p align="center">
    <img src=".readme_img/ss%20w10.png">
    </p>
  </details>
</blockquote></details>

One of the more difficult sounds to capture with modern sound equipment and DAW's is the sound of classic samplers. Although the characteristics of any sampler's output are hard to replicate, it's pretty easy to replicate the digital files they use. Often they record/store samples at less then the CD Red Book audio standard of 16bit/44.1kHz; often 8/12 bits and under 32kHz. This program allows you to take one or more of your own`.wav`, `.aiff` or `.mp3` files, degrade them to your selection, and outputs them as `.wav` or `.aiff`.

To run from a command line, simply execute with `python qddegrade.py` or `python3 qddegrade.py`

#### Dependencies
- Python 3
- tkinter
- pydub
- numpy
- ffmpeg