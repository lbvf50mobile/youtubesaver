## Using [win32 ytdl](https://github.com/ytdl-org/youtube-dl).

This file describes how to use (ytdl)[https://github.com/ytdl-org/youtube-dl] in Windows to download simple youtube video.

### Configuration

- download `youtube-dl.exe` file from link in the [INSTAlATION section](https://github.com/ytdl-org/youtube-dl#installation)
- Add fodler where `youtube-dl.exe` at the Windows `PATH` variable. Achieved in `my computer` label.
- 
```
$ youtube-dl https://youtu.be/XPmBnnon0Ek
[youtube] XPmBnnon0Ek: Downloading webpage
[youtube] XPmBnnon0Ek: Downloading video info webpage
[youtube] XPmBnnon0Ek: Downloading js player vflo4i8HU
WARNING: Requested formats are incompatible for merge and will be merged into mkv.
[download] Destination: Haddaway - What Is Love-XPmBnnon0Ek.f137.mp4
[download] 100% of 83.26MiB in 00:08
[download] Destination: Haddaway - What Is Love-XPmBnnon0Ek.f171.webm
[download] 100% of 4.58MiB in 00:00
[ffmpeg] Merging formats into "Haddaway - What Is Love-XPmBnnon0Ek.mkv"
Deleting original file Haddaway - What Is Love-XPmBnnon0Ek.f137.mp4 (pass -k to keep)
Deleting original file Haddaway - What Is Love-XPmBnnon0Ek.f171.webm (pass -k to keep)
```

