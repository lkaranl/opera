# OPERA BROWSER
OPERA DOES NOT OPERATE VIDEOS HTML5, H.264 VIDEO

# OPERA DOES NOT WORK VIDEOS HTML5, H.264
Opera for many is one of the best Browser of the moment, either for its lightness or features.
But there is something that still bother a lot for those who use Linux, which in my opinion is ignored by the developers, it does not YouTube videos that use H.264 codecs, making a headache, imagine having to switch from Browser just because of some videos in specifics (but that is increasing more and more).

But here is a very simple solution for this, the problem is in the file "libffmpeg.so"
It is located in the paste "/usr/lib/opera"

# SOLUTION
Enter the paste "Downloads"
`$cd ${HOME}/Downloads`

Download "libffmpeg.so"
`$wget https://www.dropbox.com/s/jm3hkzrlyatt6qw/opera-ffmpeg-codecs-67.0.3396.87-1-x86_64.pkg.tar.xz?dl=0`

Extract
`$tar -xvf opera-ffmpeg-codecs-67.0.3396.87-1-x86_64.pkg.tar.xz?dl=0`

Copy the file "libffmpeg.so" of the extracted file to the Opera folder
`$sudo sudo cp usr/lib/opera/lib_extra/libffmpeg.so /usr/lib/opera/`

Restart Opera

