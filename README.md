# HLS Server Sample

Use

- https://github.com/video-dev/hls.js
- https://developer.apple.com/streaming/

## Make m3u8

Check

```bash
$ mediafilesegmenter -V video.mp4
```

```
$ mkdir hls
$ mediafilesegmenter -f hls -i index.m3u8 -B media- video.mp4
```

## Setup

```
$ docker-compose up
```

