streaming-media
===============

Generate new streaming file according to the seconds. Implement as nginx plugin.

There is a `start` param which indicates the drag point.

The old ngx_http_mp4_module.c from the nginx site does not begin from the keyframe.

The old ngx_http_flv_module.c from the nginx site provides pseudo-streaming and regard `start` as the offset of the file.

