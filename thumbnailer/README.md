Thumbnailer
=========

Fork of <https://github.com/zRedShift/thumbnailer>

[![GoDoc](https://github.com/royalcat/mediautils/thumbnailer?status.svg)](https://github.com/royalcat/mediautils/thumbnailer)

Thumbnailer provides a lightning fast and memory usage efficient image, video and audio (cover art) thumbnailer via
libvips and ffmpeg C bindings, with MIME sniffing (via mimemagic), and streaming I/O support.

## License

[MIT License.](https://github.com/zRedShift/thumbnailer/blob/master/LICENSE)

## API

See the [Godoc](https://github.com/royalcat/mediautils/thumbnailer) reference.

## Dependencies

- pkg-config
- libvips 8.7.0+ compiled with libimagequant and all the formats required
- ffmpeg 5.0.0+ compiled with all the formats required
- pthread
