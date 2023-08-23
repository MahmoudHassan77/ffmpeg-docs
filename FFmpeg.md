# FFmpeg

## **What is FFmpeg?**

FF ⇒ Fast Forward , mpeg ⇒ Moving Picture Experts Group

> The MPEG group is the alliance of working groups who are behind setting many of the most important video standards being used today including the MP4 format.
> 

<aside>
💡 MPEG stands for "Moving Picture Experts Group," and it refers to a set of standards developed by a working group of experts. The MPEG standards are focused on audio and video **compression** and **coding**. They define various methods for compressing audio and video data to enable efficient storage and transmission while maintaining acceptable quality.

</aside>

### MPEG standards

1. **MPEG-1**: This standard was introduced in the early 1990s and is responsible for formats like MPEG-1 Audio Layer III (MP3) for audio compression and Video CD (VCD) for video storage.
2. **MPEG-2**: Introduced in the late 1990s, MPEG-2 is used for digital television broadcasting, DVD videos, and some digital video broadcasting standards.
3. **MPEG-4**: This standard, introduced in the late 1990s as well, is more versatile and supports various multimedia applications, including video streaming, interactive multimedia, and mobile devices. It includes codecs like H.264 (also known as AVC) and AAC (Advanced Audio Codec).
4. **MPEG-7**: This standard focuses on the description of audiovisual content, enabling better searching, indexing, and retrieval of multimedia content.
5. **MPEG-21**: This standard aims to provide a framework for multimedia applications and services, enabling the integration of various multimedia technologies.
6. **MPEG-DASH**: Dynamic Adaptive Streaming over HTTP (DASH) is an adaptive streaming protocol based on MPEG standards, allowing for efficient video streaming over the internet.
7. **MPEG-H**: MPEG-H Audio is an audio codec that supports immersive and 3D audio experiences, making it suitable for technologies like Virtual Reality (VR) and Augmented Reality (AR).

### **Characteristics**

- Open-source project
- Collection of libraries and tools
- For handling multimedia files and streams (audio/video)
- Can use it for free “Free Licence” (GPL/LGPL)

---

## **Why use FFmpeg?**

- Swiss army knife of transcoding/streaing
- Versatile (multiple functions)
- Fast
- Simple to run
- Very flexible
- Supports a very wide range of codecs, format, devices and protocols
- It is still active under development
- It has large community

![1592580187419.jpeg](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/1592580187419.jpeg)

### **FFmpeg is commonly used in**

1. **Format Conversion**: FFmpeg can convert audio and video files between different formats. This is particularly useful when you need to make media content compatible with different devices, software, or platforms.
2. **Video Compression**: FFmpeg includes various codecs and compression algorithms that allow you to reduce the size of video files without compromising too much on quality. This is important for efficient storage and streaming.
3. **Audio Manipulation**: You can use FFmpeg to manipulate audio files by changing their formats, bit rates, sample rates, and channels. It can also apply effects, normalize audio levels, and perform other audio-related tasks.
4. **Video Editing**: While FFmpeg is not a full-fledged video editing software, it can perform basic video editing tasks like cutting, trimming, merging, and concatenating video clips.
5. **Streaming**: FFmpeg supports live streaming and adaptive streaming protocols, making it suitable for broadcasting live events or creating online streaming platforms.
6. **Transcoding**: Transcoding involves converting media content from one codec to another. FFmpeg is often used for this purpose, especially when dealing with video platforms, streaming services, or different hardware devices that require specific codecs.
7. **Batch Processing**: You can automate batch processing tasks with FFmpeg, allowing you to apply the same operation to multiple files.
8. **Command-Line Interface**: FFmpeg provides a command-line interface, which gives you fine-grained control over various settings and options. This is particularly useful for advanced users and developers who want to integrate multimedia processing into scripts and applications.
9. **Customization**: FFmpeg's open-source nature allows developers to modify and extend its functionality to suit specific needs. This makes it adaptable for a wide range of projects.
10. **Cross-Platform**: FFmpeg is available for various operating systems, including Windows, macOS, Linux, and more. This cross-platform compatibility makes it accessible to users on different systems.

---

## **Who use FFmpeg?**

- **Video Streaming Platforms like Youtube, iTunes…**
- **Media Players and Editors like VLC**
- Media asset management systems
- Transcoders
- **Video Conversion Tools**
- Broadcasters
- **Live Streaming Services**
- **Video and Audio Processing Libraries**
- **Digital Signage**
- **Gaming Industry**
- etc

---

## **FFmpeg Libraries**

- **libavcodec** ⇒ contains all the encoders and decoders that FFmpeg support
- **libavformat** ⇒ has all the muxers and demuxers for dealing with various container formats like MP4, MKV, AVI, and more.
- **libavfilter** ⇒ consists of a huge number of filters that you can use to modify thee audio or video such as scaling, cropping, resizing, and more
- **libavdevices** ⇒ support several different input and output devices
- **libavutil** ⇒ contains utility functions that are used by other FFmpeg components. It includes functions for memory management, data structures, mathematics, and more
- **libswscale** ⇒ is responsible for image scaling and conversion. It's often used to adapt the dimensions and color spaces of video frames
- **libswresample** ⇒ handles audio resampling and conversion. It's used for adjusting audio sample rates, formats, and channels.
- **libpostproc** ⇒ provides post-processing functionalities for video frames. It can be used for tasks like deinterlacing, noise reduction, and image enhancement
- **libavcformat** ⇒ focuses on format conversion and supports a wide range of multimedia formats, making it useful for transcoding and format-related tasks

---

## **FFmpeg Tools**

- **ffmpeg**⇒ core tool of FFmpeg and provides a comprehensive set of options for transcoding, converting, and manipulating audio and video files. It can be used to change formats, resize videos, adjust codecs, and more
- **ffplay** ⇒ minmal tool for playing audio and video
- **ffprobe** ⇒ analyzing multimedia files and extracting information about their formats, codecs, streams, bit rates, and more
- **ffserver** ⇒ allows you to set up a multimedia streaming server. It can stream audio and video content over networks using various protocols
- **ffmpeg-avconv** ⇒ is a compatibility tool that provides a similar interface to the now-deprecated avconv command. It's useful for transitioning from avconv to FFmpeg
- **ffmpeg-resampler** ⇒ is a tool for audio resampling and conversion. It can be used to adjust audio sample rates and formats
- **ffmpegthumbnailer** ⇒ generates thumbnails from video files. It can be used to create preview images for video content.
- **qt-faststart** ⇒ rearranges the structure of MP4 or MOV files, making them suitable for streaming over the internet.
- **ffmpeg-filters** ⇒ provides documentation for FFmpeg's various filters, which can be used to modify and process multimedia content.
- **ffmpeg-scaler** ⇒ provides documentation for FFmpeg's image scaler, which can be used to resize and convert images.

---

## Install **FFmpeg**

<aside>
💡 The FFmpeg project doesn’t offer official builds of FFmpeg for any operating system, so you can build FFmpeg yourself from the source code

</aside>

- Source Code
    - Snapshot
        [https://ffmpeg.org/releases/ffmpeg-snapshot.tar.bz2](https://ffmpeg.org/releases/ffmpeg-snapshot.tar.bz2)
    - Git
        git clone  [https://ffmpeg.org/ffmpeg.git](https://ffmpeg.org/ffmpeg.git) ffmpeg
    

### Pre-built packages

- Through package manager (APT on Ubuntu, Homebrew on Mac)
- Through third-party hosted builds: [https://ffmpeg.org/download.html](https://ffmpeg.org/download) for Windows

### 1- **Mac Installation**

The easiest way to get FFmpeg installed is by Homebrew package manager 

open your terminal and type…

```jsx
brew  //to install Homebrew package manager
brew install ffmpeg  //to install ffmpeg
ffmpeg  //to check version is installed
```

### 2- Ubuntu **Installation**

The easiest way to get FFmpeg installed is by APT package manager 
open your terminal and type…

```jsx
sudo apt update   //to get latest version of apt
sudo apt install ffmpeg  //to install ffmpeg
ffmpeg  //to check version is installed
```

### 3- Windows **Installation**

1. go to [https://ffmpeg.org/download.html](https://ffmpeg.org/download.html)

1. Get your executable file for windows

2. Choose the best build for you from 
- master builds (full or essentials)
- release builds (full or essentials)
release essential is a good choice

3. extract the downloaded file

4. add bin folder in extraxted folder to PATH environment variables 

5. type in your terminal ⇒ ffmpeg to check ffmpeg version

![Screenshot 2023-08-22 093920.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_093920.png)

![Screenshot 2023-08-22 095525.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_095525.png)

![Screenshot 2023-08-22 095653.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_095653.png)

---

# #**FFprobe**

It is a very powerful tool that can use it to extract and show various information about the media for example the resolution of the video, codec information, number of channels in an audio stream, etc.

### **How to use FFprobe**

```jsx
ffprobe [options] [video (name/url)]
```

1- Simple use

```jsx
ffprobe input.mp4 // [input.mp4] may be local video or video url
```

![Screenshot 2023-08-22 185701.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_185701.png)

 

2- Remove FFprobr banner

```jsx
ffprobe -hide_banner js.mp4
```

![Screenshot 2023-08-22 190225.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_190225.png)

3- logs only errors

```bash
ffprobe -v error js.mp4
```

4- show input format

```bash
ffprobe -v error js.mp4 -show_format
```

![Screenshot 2023-08-22 192255.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_192255.png)

5- show input streams

```bash
ffprobe -v error js.mp4 -show_streams
```

It will show all information about input video strams (codec name - width - height - codec type - etc)

![Screenshot 2023-08-22 193809.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_193809.png)

5- show video packets

```bash
ffprobe -v error js.mp4 -show_packets
```

![Screenshot 2023-08-22 194619.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_194619.png)

6- show video frames

```bash
ffprobe -v error js.mp4 -show_frames
```

![Screenshot 2023-08-22 194900.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_194900.png)

7- Select video/audio stream

```bash
ffprobe -v error js.mp4 -show_streams -select_streams v
```

![Screenshot 2023-08-22 204418.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_204418.png)

8- Format output

```bash
ffprobe -v error js.mp4 -show_streams -select_streams v -print_format json
```

![Screenshot 2023-08-22 205046.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_205046.png)

9- **Display a specific property**

```bash
ffprobe -v error js.mp4 -show_streams -select_streams v -show_entries stream=codec_name
```

![Screenshot 2023-08-22 205606.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_205606.png)

```bash
ffprobe -v error js.mp4  -show_entries format=format_long_name -print_format default
```

![Screenshot 2023-08-22 205922.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_205922.png)

** if you want to remove wrapper **

```bash
ffprobe -v error js.mp4 -show_entries format=format_long_name -print_format default=noprint_wrappers=1
```

![Screenshot 2023-08-22 210219.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_210219.png)

** if you want to display only value without the key**

```bash
ffprobe -v error js.mp4 -show_entries format=format_long_name -print_format default=noprint_wrappers=1:nokey=1
```

![Screenshot 2023-08-22 210832.png](FFmpeg%20bca5d9db303e4b2cac2889839c3a0d78/Screenshot_2023-08-22_210832.png)

<aside>
💡 There are many other options available; you can explore them through the official website.

</aside>

---

# #**FFplay**

It allows you to play various audio and video files directly from the command line without the need for a separate media player application.

### **How to use FFplay**

```bash
ffplay [options] [input file or url]
```

1- Simple use

```bash
ffplay source.mp4
```

2- Play video without unnecessary logs

```bash
ffplay -v error source.mp4
```

3- Play video with spacific width and height

```bash
ffplay -v error source.mp4 -x 1080 -y 900
```

4- Display video with no border 

```bash
ffplay -v error source.mp4 -x 1080 -y 900 -noborder
```

5- Remove black area around the video 

```bash
ffplay -v error source.mp4 -x 1080
```

6- change the window position on the screen

```bash
ffplay -v error source.mp4 -top 0 -left 0
```

7- display full screen video

```bash
ffplay -v error source.mp4 -fs
```

8- Disable audio playback

```bash
ffplay -v error source.mp4 -an
```

9-Disable video playback

```bash
ffplay -v error source.mp4 -vn
```

10- Change displayed mode 

```bash
ffplay -v error source.mp4 -showmode (waves | video | rdft)
```

11- Repeat the played video

```bash
ffplay -v error source.mp4  -loop 0
```

12-  **Play a specific section of a video**

```bash
ffplay -ss 30 -t 10 source.mp4
```

13- Disable subtitles

```bash
ffplay -v error -sn source.mp4 
```

Shortcuts you can use while a video is playing.

```markdown
- space => resume / pause
- m => mute / unmute
- f => fullscreen
- double lift click =>  fullscreen
- / or 9 => volume down
- * or 0 => volume up
- w => change mode (audio - video - waves)
- s => frame step
- → => forward 10s
- ← => back 10s
- ↑ => forward 1m
- ↓ => back 1m
- Esc => quit
```

<aside>
💡 There are many other options available; you can explore them through the official website.

</aside>

---