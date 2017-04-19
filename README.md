# avi2dvd
Converts an AVI file to a DVD file structure and writes it to DVD in 2-minute chapters.

# Requirements:
You will need the following open source utilities on your system, which
most LINUX-based O/S have pre-built packages of:
 1. mplayer    http://www.mplayerhq.hu
 2. growisofs  http://fy.chalmers.se/~appro/linux/DVD+RW
 3. mencoder   http://www.mplayerhq.hu
 4. dvdauthor  http://dvdauthor.sourceforge.net
You also need to have a DVD-writer, some blank DVD's etc...

Note: The average AVI-movie to DVD conversion takes around 30 minutes on a
      medium spec machine. A 700MB avi file results in a 3.5GB DVD image, so
      ensure you have enough available disk space. The resulting DVD image
      is not removed if this script does not detect a DVD writer, in order
      for you to manually burn the DVD later on. This DVD image is in the
      same directory as the source .avi file, so do your own housekeeping
      after you have manually burned the DVD.
