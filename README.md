# my-ffmpeg-commands

````
ffmpeg -i video.mp4 -vcodec libx264 -crf 27 -preset veryfast -c:a copy -s 960x540 video-960x540.mp4
`````

#mp4 to webm
`````
ffmpeg -i generique-goutte-eau-cut.mp4 -vcodec libvpx -acodec libvorbis -cpu-used 5 -threads 8 "${0%%.mp4}.webm"
````

ffmpeg -i movie.mov -vcodec copy -acodec copy out.mp4
