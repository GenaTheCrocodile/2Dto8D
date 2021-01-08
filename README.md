# 2Dto8D

Script for applying 8D effect on an audio

## Requirements

```bash
sudo pacman -S sox # Install "Sound eXchange" package
pip install --user pydub
```
## Usage

```bash
Usage: 2dto8d  "input.mp3"  "output.mp3"  \
[reverberance (0 - 100, default 50)]  [Min. fade volume (default -15.0 dB)]  [Channel switching time (default 3.5 seconds)]  [Fade time (default 1 second)]
```
