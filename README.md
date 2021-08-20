# wssc demo

### Use

Edit wssc.html and change the following line

``` javascript
var ws_server = "wss://localhost:12345/";
```

to the appropriate URL.

Use your email address and the UUID you were provided with.

You can use any audio codec that *ffmpeg* generally supports, it's been tested
with at least; mp3, Opus & FLAC.

If you have 16 bit, mono 16 KHz WAVE audio, then you can use that and wssc
won't need to transcode the audio.

### License

This is licensed under the MIT license, see *LICENSE* for details.
