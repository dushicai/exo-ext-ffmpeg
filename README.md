# FFmpeg extension

The [FFmpeg extension](https://github.com/google/ExoPlayer/tree/release-v2/extensions/ffmpeg) supports decoding a variety of different audio sample formats. You can choose which decoders to include by passing command line arguments to FFmpeg’s `configure` script:

| Sample format | Argument(s) to `configure`                 |
| ------------- | ------------------------------------------ |
| Vorbis        | –enable-decoder=vorbis                     |
| Opus          | –enable-decoder=opus                       |
| FLAC          | –enable-decoder=flac                       |
| ALAC          | –enable-decoder=alac                       |
| PCM μ-law     | –enable-decoder=pcm_mulaw                  |
| PCM A-law     | –enable-decoder=pcm_alaw                   |
| MP1, MP2, MP3 | –enable-decoder=mp3                        |
| AMR-NB        | –enable-decoder=amrnb                      |
| AMR-WB        | –enable-decoder=amrwb                      |
| AAC           | –enable-decoder=aac                        |
| AC-3          | –enable-decoder=ac3                        |
| E-AC-3        | –enable-decoder=eac3                       |
| DTS, DTS-HD   | –enable-decoder=dca                        |
| TrueHD        | –enable-decoder=mlp –enable-decoder=truehd |

See the extension’s [README.md](https://github.com/google/ExoPlayer/tree/release-v2/extensions/ffmpeg/README.md) for an example command line to `configure`.

