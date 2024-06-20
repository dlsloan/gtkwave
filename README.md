# GTKWave

## Installation

1) install pakages `sudo apt-get install libjudy-dev libbz2-dev liblzma-dev libgconf2-dev libgtk2.0-dev tcl-dev tk-dev gperf gtk2-engines-pixbuf`
2) use gtkwave-gtk3 `cd repo-dir/gtkwave3-gtk3`
3) `./autogen.sh`
4) `./configure --enable-judy --enable-struct-pack --with-gconf`
5) `make`
6) `sudo make install` (as root)

Make sure you copy the `.gtkwaverc` file to your home directory or to your
VCD project directory.  It contains the prefs for a good configuration
that most people find ergonomic.  It is not strictly necessary however.
