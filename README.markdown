Video Fixer
===========

This is a script I wrote for fixing videos after importing them from my iPhone. The files are huge and when I would like to keep the videos on my phone I decided to reencode them to reduce their size significantly. This script uses HandBrake and ffmpeg to do the heavy lifting. HandBrake does the encoding and ffmpeg fixes rotation problems.

HandBrake and ffmpeg must both be in your PATH so this script can find them.

Reencode a video for iPhone:
----------------------------
```
video_fixer convert /path/to/video.MOV /path/to/output/directory/ --for iPhone
```

Rotate a video clockwise:
-------------------------
```
video_fixer rotate /path/to/video.mp4 right
```
