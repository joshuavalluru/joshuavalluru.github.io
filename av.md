## Audio/Video Software Tools/Applications
---

### Video Editing
 
For most of the video editing requirements I use FFMPEG which is an open source video manipulation software. FFMPEG has a powerful command-line interface for controlling and manipulating almost all the parameters of a video. I mainly use it for cropping, transcoding and mixing videos. 
 
Uncompressed video is quite large for streaming on internet so video is always compressed with codecs like H.264. The more a video is compressed, the smaller size (bytes) it uses while compromising on video quality. Once a video is ready for streaming, I encode it into multiple quality streams - low, medium, high for instance - to be used for clients of different network (bandwidth) conditions. I do it by manipulating resolution, framerate and bitrate parameters in FFMpeg.


### Making Multimedia Content

For advanced creation of multimedia content, I use iMovie. It was a rich UI for splitting and combining audio/video streams within a video file. It allows me to combine videos, change audio streams (for instance, adding a background audio) with a simple UI and visualize the video before publishing it .
Comfortable with music production software like AbletonLive.


### Audio Editing / Enhancement
 
I extract the audio stream from the video first using FFMpeg and then use Audacity, which is another open source audio editing tool for enhancing and combining audio streams. It allows me to do things like de-noising, adjusting the gain,  speech enhancement etc. Once the audio stream is ready, I can put it back into the video using iMovie or FFmpeg.
