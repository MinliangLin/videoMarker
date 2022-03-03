This is a simple viewer of videos with markers.

## Get Started

First, launch a web server locally. For example, you may use the below command in python:

```sh
python3 -m http.server
```

Or `RangeHTTPServer` for faster access to video:

```sh
python3 -m RangeHTTPServer
```

Second, if your data (videos and shot files) are served on web, nothing to do.

If your data is on local, copy or link them into this project folder, e.g.

```
mkdir -p data
ln -s /SOMEWHERE/MY_VIDEO.mp4 data/MY_VIDEO.mp4
ln -s /SOMEWHERE/MY_VIDEO_SHOT.txt data/MY_VIDEO_SHOT.txt
```

Third, put the url in `input` and press `reload`.
