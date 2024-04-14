# B Movie Player

This movie player can stream MP4 files hosted on the web and play in your browser.

## Features
- Support MP4 files
- Support SRT and WebVTT subtitles
- Support auto-loading a subtitle. Subtitle file name is based on MP4 file name
  - E.g. if a video file is named video1.mp4, the player will try loading video1.srt and video1.vtt
- Support loading video file from a search parameter (video-url)
  - E.g. https://brianwoo.github.io/b_movie_player/?video-url=http%3A%2F%2Fcommondatastorage.googleapis.com%2Fgtv-videos-bucket%2Fsample%2FBigBuckBunny.mp4
  - Make sure URL is URL-encoded
- Support touch control
  - Double click middle of the player (pause / play)
  - Double click right side of the player (fast-forward 10s)
  - Double click left side of the player (fast-rewind 10s)