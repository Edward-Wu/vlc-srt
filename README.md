# vlc-srt
vlc3.0 with srt

VLC version 3.0 claims to support SRT, but it does not implement the parser of streamid parameter, which results in a big limitation of usage scenarios.

This patch is used to replace the file with the same name under the modules/access directory, only for vlc version 3.0（not version 4.0）and only for playing srt url. If you want to push srt url, please modify srt file in the modules/access_output by yourself.

For specific compilation methods of VLC, please refer to the official website or:

https://blog.csdn.net/wutong_login/article/details/104744379
