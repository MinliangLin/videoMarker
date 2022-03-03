This is a simple viewer of videos with markers.

## Get Started

First, launch a web server that support Range requests. For example, the below command is for python users:

```sh
python -m RangeHTTPServer
```

Second, if your data (videos and shot files) are served on web, nothing to do.

If your data is on local, copy or link them into this project folder, e.g.

```
mkdir -p data
ln -s /SOMEWHERE/MY_VIDEO.mp4 data/MY_VIDEO.mp4
ln -s /SOMEWHERE/MY_VIDEO_SHOT.txt data/MY_VIDEO_SHOT.txt
```

Third, open your brower on http://localhost:8000. Put the url of data into input fields and press `reload`.
