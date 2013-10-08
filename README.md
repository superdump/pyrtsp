# pyrtsp

Quick Python RTSP server test

## Dependencies

* GStreamer 1.x
* gst-python
* pygobject
* pygi
* gst-rtsp-server

## What is it?

This is a quickly hacked together RTSP server that uses a video test source to
generate a video stream, encode it to h.264 using x264, payload it for RTP and
stream it using gst-rtsp-server.
