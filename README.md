# my-ffmpeg-commands

````
ffmpeg -i video.mp4 -vcodec libx264 -crf 27 -preset veryfast -c:a copy -s 960x540 video-960x540.mp4
