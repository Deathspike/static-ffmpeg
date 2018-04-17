### static-ffmpeg

Docker image with static ffmpeg and ffprobe binaries. To be run as or part of
multi-stage build when ffmpeg is needed. Binaries are built as hardened PIE binaries
with no external dependencies (uses musl from alpine instead of glibc).

Built with
libmp3lame,
libfdk-aac,
libvorbis,
libopus,
libtheora,
libvpx,
libx264,
libx265
and all default native ffmpeg codecs.