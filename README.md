# FFmpeg for Android ARMv8 & ARMv7
~Should I Stay or Should I Go
It's a personal project, don't expect a dev master blaster (12" Version).

Static binaries of FFmpeg 8.1 and FFprobe 8.1 using a modern NDK, with full support for:
- **Native libraries:** `libffmpeg_jni.so` (with `JavaVM` and `MediaCodec` hardware acceleration) and `libffprobe_bin.so`.
- **Hardware:** `h264_mediacodec`, `hevc_mediacodec`, and GPU/VPU-based decoding
- **Audio:** `libfdk-aac` (`aac_he_v2`), `libopus`, and `libmp3lame`
- **Video:** `libx264` and `libvpx` (VP8 / VP9)
