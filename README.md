# heroku-buildpack-ffmpeg-latest

A Heroku buildpack for a working combination of youtube-dl and ffmpeg.
Latest static builds are always downloaded.
- [ffmpeg](http://johnvansickle.com/ffmpeg/).
- [youtube-dl](https://yt-dl.org/downloads/latest/)

## Usage

```
heroku buildpacks:add https://github.com/veeraya/heroku-buildpack-ffmpeg-latest.git
```

Forked from https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest to include youtube-dl and set locale to enable unicode character in output file name.