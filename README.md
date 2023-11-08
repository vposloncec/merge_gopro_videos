# Merge GoPro / DJI video chunks

This util tries to merge chunks of recordings that have been split in multiple parts.

This often happens on GoPros and DJI cameras where recordings are split in 4gb parts.
Script takes multiple files (by default whole folder) and tries to create groups of
files that should be merged together in a single video.

By default it will group files like DJI_1234_001.mp4, DJI_1234_002.mp4 together in a single video

For more info, see
```
merge_gopro_videos --help
```
