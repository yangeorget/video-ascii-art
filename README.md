# Video Ascii Art

A one-page HTML file that converts the camera stream into mesmerizing Ascii art.

## As a camera

Serve this page, eg:
```bash
python -m http.server 8080
```

Launch OBS:
```
open /Applications/OBS.app --args --use-fake-ui-for-media-stream
```

Use a browser source.
- point to http://localhost:8080/obs.html
- set the width to 1280 and the height to 720

Start the camera.
- make sure the Output Type is Source