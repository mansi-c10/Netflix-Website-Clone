# Netflix-Website-Clone

# What is Audio Streaming & Video Streaming?

Livestreaming technology is commonly used to relay live events such as sports, concerts, and TV or radio programs. Instead of playing a finite file, livestreaming involves transmitting media “live” to computers and devices. Here are some key points:

1. Static Media vs. Livestreamed Media:
  - Static media refers to files (like MP3s or WebM files) that sit on a server and can be delivered to the browser via progressive download.
  - Livestreamed media lacks a finite start and end time. It’s a continuous stream of data created on the fly and relayed from the server to the browser. Adaptive streaming is often used for this purpose.

2. Adaptive Streaming:
  - The goal of adaptive streaming is to keep the player synchronized with the stream, especially in cases of low bandwidth.
  - Formats that facilitate adaptive streaming break streams into small segments available at different qualities and bit rates.
    
3. Streaming Protocols:
  - HTTP (Hypertext Transfer Protocol) is the most commonly supported protocol for transferring media on demand or live.
  - RTMP (Real Time Messaging Protocol) is a proprietary protocol supported by Adobe Flash. It comes in various flavors, including RTMPE (encrypted), RTMPS (secure over TLS/SSL), and RTMPT (encapsulated within HTTP requests)
    
Whether it’s live events, on-demand media, or adaptive streaming, the world of audio and video streaming continues to evolve, providing seamless experiences across devices. 

# How audio and video stream happens in Netflix and how we combine them?

1. Audio Streaming at Netflix:
  - Studio-Quality Experience: Netflix recognizes the importance of sound in entertainment. While much attention is given to video quality improvements (like 4K and HDR), sound quality is equally crucial.
    
  - Challenges: Creative choices in series mixes are becoming bolder and more cinematic, pushing the limits of encoding quality. Ensuring high-quality audio across devices is essential.
    
  - Adaptive Streaming for Audio: To address varying network conditions, Netflix employs adaptive streaming for audio. Just like adaptive streaming adjusts video quality based on bandwidth, it dynamically adjusts audio quality during playback1.
    
  - Formats Supported:
    * 5.1 Surround Audio: Netflix started streaming 5.1 surround audio in 2010.
    * Dolby Atmos: In 2016, Netflix introduced Dolby Atmos for an immersive audio experience.
    * Studio Quality Sound: The goal is to bring studio-quality sound to members worldwide, even if they don’t have a state-of-the-art home theater system.
    
2. Combining Audio and Video:
  - Essence of Storytelling: Audio and video components combine to evoke the essence of storytelling. From violin melodies to thunderous sound effects, they work together to create emotional impact.
    
  - Netflix’s Approach: Netflix maintains creative intent by supporting initiatives like HDR and Netflix Calibrated Mode for video. Similarly, they strive to ensure brilliant audio experiences for viewers, regardless of their playback setup.
    
  - Future Trends: As the streaming landscape evolves, we may see further integration of audio and video platforms, merging the best of both worlds.

# How we use HLS in it and give them support?

- What is HLS?
  * HLS stands for HTTP Live Streaming.
  * It is a media streaming protocol designed to deliver audio-visual content to viewers over the internet.
  * Created by Apple, HLS facilitates content transportation from media servers to viewer screens, including mobile devices, desktops, tablets, and smart TVs.
  * It is widely used for distributing both live and on-demand media files.
  * For anyone targeting Apple devices, HLS is the go-to option. In fact, it’s mandatory for App Store apps offering video content longer than 10 minutes or heavier than 5MB.
  * HLS dynamically adapts to network conditions, ensuring excellent viewing experiences across devices and playback platforms.
  * Despite its Apple origins, HLS has become the most preferred protocol for distributing video content across various platforms and browsers.
  
- How Does HLS Work?
  * Segmented Delivery: HLS breaks video content into small segments, typically between 2 to 10 seconds in length.
  * These segments are delivered to the viewer’s device via HTTP requests.
  * The video player on the device then reassembles these segments to play the video seamlessly.
  * Adaptive bitrate streaming is a key feature of HLS. It adjusts streams based on bandwidth fluctuations, ensuring uninterrupted playback for viewers.
  
- Broad Support and Industry Standard:
  * HLS enjoys broad support among most streaming and distribution platforms.
  * It allows you to distribute content across geographies, making it ideal for streaming video to large audiences.
  * Since HLS is an industry standard, it can be played on Mac, Android, Microsoft, and Linux devices, making it popular for over-the-web playback.

# How we convert videos in 720p and 360p?

1. Online Video Resizer:
  You can use an online tool like Video Resizer to change the resolution of your videos without compromising quality.
  Here’s how:
  - Open Video Resizer in your browser from any device (PC, phone, or tablet).
  - Click ‘Open file’ and upload your video by dragging it or selecting it from a folder.
  - Wait for the upload (larger files may take up to 10 minutes; small clips process quickly).
  - Select the desired size (e.g., 720p or 360p) from the available dimensions.
  - Optionally, use other tools to edit and enhance your video (add texts, subtitles, effects, etc.).
  - Click ‘Save’, and your resized video will be downloaded in the chosen format, ready for use and publishing.

3. FlexClip Video Converter:
    FlexClip is another excellent online tool that allows you to change video resolutions.
    Input your video and set the output resolution to 360p or 720p.
    It’s free, requires no download, and reduces video sizes as well.

4. Aconvert.com:
  If you specifically want to resize from 360p to 720p, you can use Aconvert.com:
  Upload your video.
  - Select “Change size, bitrate, or frame rate” in the options.
  - From the Video Size drop-down list, choose “1080X720 (720p)” as the target resolution.
  - Click “Convert Now!” to start the conversion
