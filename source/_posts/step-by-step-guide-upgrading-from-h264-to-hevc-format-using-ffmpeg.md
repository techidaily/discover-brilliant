---
title: "Step-by-Step Guide: Upgrading From H264 to HEVC Format Using FFmpeg"
date: 2024-09-29T20:47:25.733Z
updated: 2024-09-30T16:54:17.794Z
categories:
  - macxdvd
thumbnail: https://thmb.techidaily.com/560da63c54300a3a876ba2cfdab00c7431c7174d8c1f2c53836ffd296ae56332.jpg
---

## Step-by-Step Guide: Upgrading From H264 to HEVC Format Using FFmpeg

[![macx video converter pro icon](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/icon11.png)](https://tools.techidaily.com/macxdvd/products/)

* [MacX Video Converter Pro](https://tools.techidaily.com/macxdvd/products/)
* [Guide](https://tools.techidaily.com/macxdvd/products/)
* [Support](https://tools.techidaily.com/macxdvd/products/)
* [Free Download](https://tools.techidaily.com/macxdvd/products/)

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/icon7.png) [Home](https://tools.techidaily.com/macxdvd/products/) \> [Video](https://tools.techidaily.com/macxdvd/products/) \> [HEVC](https://tools.techidaily.com/macxdvd/products/) \> FFmpeg H.264 to H.265

## FFmpeg Tutorial - Encode H264 to H265/HEVC with No Quality Loss

_You can turn H264 format to H265/HEVC with FFmpeg indeed though it may be a little bit complicated and not user friendly. Here we go to check how to encode H264 codec format to H265 HEVC with no quality loss._ 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/icon6.png) By [Candice Liu](https://tools.techidaily.com/macxdvd/products/) ｜Last updated on Jan 13, 2021

* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-fa.jpg)](https://www.facebook.com/sharer/sharer.php?u=https://www.macxdvd.com/mac-dvd-video-converter-how-to/convert-h265-to-h264-ffmpeg.htm)
* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-tw.jpg)](https://twitter.com/intent/tweet?url=https://www.macxdvd.com/mac-dvd-video-converter-how-to/convert-h265-to-h264-ffmpeg.htm&text=)

* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-go.jpg)](https://pinterest.com/pin/create/button/?url=https://www.macxdvd.com/mac-dvd-video-converter-how-to/convert-h265-to-h264-ffmpeg.htm&media=&description=)
* [![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-in.jpg)](https://www.linkedin.com/shareArticle?mini=true&url=https://www.macxdvd.com/mac-dvd-video-converter-how-to/convert-h265-to-h264-ffmpeg.htm&title=&summary=&source=)

H.265 (also known as HEVC) can offer 50–75% more compression efficiency compared to H.264 video, while retaining the same visual quality. Thus if your hardware is available for H265 files, it's a nice option to [transcode H264 to H265](https://tools.techidaily.com/macxdvd/products/) since you can not only save storage space of your devices, but also enjoy the equal quality of H264 videos. Moreover, HEVC playback is available on iPhone iPad running on iOS 11 and all Macs on High Sierra, with encoding/decoding hardware acceleration on newer iOS devices and the latest Macs offering faster performance combined with less battery drain.

For this purpose, **FFmpeg** is regarded as the first consideration since it has support for HEVC encoding using the x265 encoder. 

## Table of Contents

* [Part 1: \[Tutorial\] Convert H264 to H265 with FFmpeg](https://tools.techidaily.com/macxdvd/products/)
* [Part 2: Best FFmpeg Alternative to Create HEVC Video from H264 without Error](https://tools.techidaily.com/macxdvd/products/)

## \[Tutorial\] Convert H264 to H265 with FFmpeg

**Step 1:** [Free download FFmpeg static zip file](http://ffmpeg.zeranoe.com/builds/) on your computer. Please note that you should download the right one based on system type.   
 **Step 2:** Install FFmpeg on your computer. Take Windows 7 (32 bit) as an example, unzip file and open the command prompt with administrator's right. Enable FFmpeg in the command line: right-click on Computer and choose Properties > Advanced system settings > Environment Variables. In the Users variables, click New... button and enter Path for variable name; c:\\ffmpeg\\bin for Variable value. 

![free convert h264 to H265 ffmpeg](https://www.macxdvd.com/mac-dvd-video-converter-how-to/article-image/ffmpeg-h264-to-h265-1.jpg) 

**Step 3:** Similar to [convert MKV HEVC to H264 MP4 with FFmpeg](https://tools.techidaily.com/macxdvd/products/), you need enter a command line. Now type in ffmpeg -i input.mp4 -c:v libx265 -preset medium -x265-params crf=28 -c:a aac -strict experimental -b:a 128k output.mp4 in the command line to switch H264 video codec to H265 via FFmpeg fast and losslessly. I converted Star Wars: The Force Awakens Official Teaser H264 to H265 as an example. It takes me only 15 seconds to transcode this H264 video to HEVC with FFmpeg.   
_Input info: starwars.mp4 video: H264 104 kb/s 11.99 fps; audio: aac, 44100Hz, stereo 125 kb/s_ 
_Duration: 00:01:59.51; bitrate: 235 kb/s; file size: 3.35 MB; resolution:1920×1080p_

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136615/26400" target="_top" id="2136615">
  <img src="//a.impactradius-go.com/display-ad/26400-2136615" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136615/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### FFmpeg Possible Errors When Converting H264 to H265

It would be nice that you turn MP4 H264 to HEVC smoothly. But sometimes things are not going so well. You may encounter some error when converting H264 to H265 such as FFmpeg crashes on halfway and FFmpeg doesn't work. On account of that you need type the specific command line, there is a great possibility that you mistake a letter or blank space, which will result in ffmpeg doesn't work. Or your file cannot be read though this format seems to be supported by FFmpeg. That's because even if ffmpeg can read the container format, it may not support all its codecs. Please consult the [supported codec list in the ffmpeg documentation](https://www.ffmpeg.org/general.html).

## Best FFmpeg Alternative to Create HEVC Video from H264 without Error

If you don't want any bother with FFmpeg H264 to H265 video processing issues, here a FFmpeg alternative - [**MacX Video Converter Pro**](https://tools.techidaily.com/macxdvd/products/) is suggested to decode 4K H264 to 4K H265 or encode to H.264 from H.265 with fast speed and original quality. Unlike FFmpeg's complicated command lines, this H265/HEVC converter enables you to transcode H.264 to HEVC within 3 steps and several clicks. Even a beginner can get the hang of it within one minute. 

**Step 1: Load H264 files.**   
 Free download the HEVC decoder on Mac or Windows version for Windows PCs (32bit or 64 bit) and launch it. Then click on **\+ Video**, choose the target H264 file from the pop up window, tap Open to import H.264 video to the program. 

**Step 2: Choose H265/HEVC as output format.**  
 Choose HEVC as the output format. With 350+ built-in preset profiles, you can not only re-encode H.264 to H.265, but also transcode H.265 to H.264, VP8 to VP9, VOB to MP4, AVI to MOV, MKV to MP4, etc. for playing on iPhone X/8/8/7/6S/6 Plus, iPad, Android. Here I've pick **HEVC**, without changing resolutions. You can also choose **4K MP4 Video** to up-convert AVCHD to 4K HEVC. 

![transcode hevc h264 to h265](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../mac-video-converter-pro/step-image/vcp-hevc-mp4-1.jpg) 

**Step 3: Optimise settings for H.264 to H.265 Conversion**   
Do some tweaks to optimise H264 codec to H265 video processing. Before the conversion, you can do some settings to improve the processing speed, and enhance the output video quality. 

_**Tip #1**_ Improve H264 to H265 processing speed: In the lower right corner of the main interface, check the box of **Hardware Encoder** to activate Intel QSV hardware acceleration, which will improve the speed up to 5 times faster than usual.   

Also, click Options icon on the top of the panel and choose the maximum number from the **CPU Core Use** drop-down list to take advantages of multi-core CPU utility. It will exceedingly free up your CPU for other tasks like video playback, web browsing. 

_**Tip #2**_ Enhance output HEVC video quality: Tick box of Use High Quality Engine and **Deinterlacing** to maximize image quality dynamically for the output HEVC/H265 videos. 

**Step 4: Start converting H264 to HEVC/H265.**   
 Click on **Browse** to specify the output folder path. Then tap **RUN** icon, you'll get a HEVC codec MP4 video from H264 at the drop of a hat. For the same starwars.mp4 video above, merely 4 seconds are needed to make H264 converted to HEVC. 

**References**

* _[What's HEVC](https://tools.techidaily.com/macxdvd/products/): HEVC is the short of High Efficiency Video Coding, also known as H.265\. The HEVC/H.265 substantially improves the data compression ratio for videos, thus saving a massive bandwidth and ensuring a 50% bit rate reduction at the same level of video quality._
* _[HEVC vs H.264](https://tools.techidaily.com/macxdvd/products/): Both codecs work by comparing different parts of a video frame in order to find the ones that are redundant within the subsequent frames. These areas are replaced with a short information, describing the original pixels. What differs HEVC/H.265 from H.264 is the ability to expand the size of these areas into bigger or smaller blocks, called CTU in the HEVC/H.265._
* _[FFmpeg](https://www.ffmpeg.org/): FFmpeg is the leading multimedia framework, able to decode, encode, transcode, mux, demux, stream, filter and play pretty much anything that humans and machines have created. It supports the most obscure ancient formats up to the cutting edge._

ABOUT THE AUTHOR

![author- candice](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/candice.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880940/19272" target="_top" id="1880940">
  <img src="//a.impactradius-go.com/display-ad/19272-1880940" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880940/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[Candice Liu ![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/share-in1.jpg)](https://www.linkedin.com/in/candice-liu-444483a3/) 

Candice's particularly skilled in writing and sharing video-related contents. Her guides cover from deep-seated video/audio parameters, to media entertainment on different platforms. She also enjoys shooting and processing videos by herself for a more reliable basis of informative info with her articles, which are never at the expense of eliminating an entertaining read.

Related Articles

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic7.jpg)

[Best Free HEVC H.264 Decoder Program](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic6.jpg)

[Convert YouTube Videos to HEVC H.265 Codec Format](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic5.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129042/19576" target="_top" id="2129042">
  <img src="//a.impactradius-go.com/display-ad/19576-2129042" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129042/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[Handbrake Tutorial: How to Decode X265 to X264 Fast](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic4.jpg)

[How to Convert MP4 to HEVC H.265 Codec Format](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic3.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151893/7443" target="_top" id="2151893">
  <img src="//a.impactradius-go.com/display-ad/7443-2151893" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151893/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[Simple Solution to Convert MKV to HEVC for Faster Uploading to YouTube](https://tools.techidaily.com/macxdvd/products/) 

![](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../image-style/new-seo/pic2.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134499/19576" target="_top" id="2134499">
  <img src="//a.impactradius-go.com/display-ad/19576-2134499" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134499/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[Fastest 4K HEVC to MP4 Converter for Mac and PC](https://www.macxdvd.com/mac-video-converter-pro/h265-hevc-to-mp4-converter-free.htm
) 

![Digiarty Software](https://www.macxdvd.com/mac-dvd-video-converter-how-to/../icon/logo.png) 

Digiarty Software, Inc. (MacXDVD) is a leader in delivering stable multimedia software applications for worldwide users since its establishment in 2006.

<!-- affiliate ads begin -->
<span id="1983552">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983552.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983552">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983552.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983552%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983552/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Hot Products

* [MacX DVD Ripper Pro](https://tools.techidaily.com/macxdvd/products/)
* [MacX Video Converter Pro](https://tools.techidaily.com/macxdvd/products/)
* [MacX MediaTrans](https://tools.techidaily.com/macxdvd/products/)

### Tips and Tricks

* [DVD Topics >>](https://tools.techidaily.com/macxdvd/products/)
* [Video Solutions >>](https://tools.techidaily.com/macxdvd/products/)
* [Data Transfer >>](https://tools.techidaily.com/macxdvd/products/)
* [Online Video >>](https://tools.techidaily.com/macxdvd/products/)
* [Hot Topics >>](https://tools.techidaily.com/macxdvd/products/)

### Company

* [About Us >>](https://tools.techidaily.com/macxdvd/products/)
* [Tech & Sales FAQ >>](https://tools.techidaily.com/macxdvd/products/)
* [User Guides >>](https://tools.techidaily.com/macxdvd/products/)
* [Contact Us >>](https://tools.techidaily.com/macxdvd/products/)
* [Partner >>](https://tools.techidaily.com/macxdvd/products/)

[Home](https://tools.techidaily.com/macxdvd/products/) | [About](https://tools.techidaily.com/macxdvd/products/) | [Privacy Policy](https://tools.techidaily.com/macxdvd/products/) | [Terms and Conditions](https://tools.techidaily.com/macxdvd/products/) | [License Agreement](https://tools.techidaily.com/macxdvd/products/) | [Resource](https://tools.techidaily.com/macxdvd/products/) | [News](https://tools.techidaily.com/macxdvd/products/) | [Contact Us](https://tools.techidaily.com/macxdvd/products/)

Copyright © 2024 Digiarty Software, Inc (MacXDVD). All rights reserved

Apple, the Apple logo, Mac, iPhone, iPad, iPod and iTunes are trademarks of Apple Inc, registered in the U.S. and other countries.  
Digiarty Software is not developed by or affiliated with Apple Inc.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-iphone-macro-and-close-up-photography-tips/"><u>[New] 2024 Approved IPhone Macro and Close-Up Photography Tips</u></a></li>
<li><a href="https://article-files.techidaily.com/new-best-practices-for-identifying-premier-free-srt-translation-services-for-2024/"><u>[New] Best Practices for Identifying Premier Free SRT Translation Services for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-ranked-alternatives-to-sporting-events-in-firstrow-views-for-2024/"><u>[New] Ranked Alternatives to Sporting Events in Firstrow Views for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-screenstreamer-pro-cutting-edge-review-for-march-2023/"><u>2024 Approved ScreenStreamer Pro Cutting-Edge Review for March 2023</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/best-video-grabbers-for-windows-11-pc-for-2024/"><u>Best Video Grabbers for Windows 11 PC for 2024</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/comparatif-dvd-vs-blu-ray-vs-fichier-numerique-quel-offre-la-plus-grande-valeur/"><u>Comparatif DVD Vs. Blu-Ray Vs. Fichier Numérique : Quel Offre La Plus Grande Valeur?</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/effective-techniques-to-slash-your-videos-size-by-up-to-90-preserving-quality/"><u>Effective Techniques to Slash Your Video's Size by Up to 90%, Preserving Quality</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/faqs-on-handbrakes-gpu-enhanced-video-transcoding-everything-you-need-to-know/"><u>FAQs on Handbrake's GPU-Enhanced Video Transcoding: Everything You Need to Know</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/how-to-correct-your-dvds-incorrect-display-settings-with-our-thorough-guide/"><u>How to Correct Your DVD's Incorrect Display Settings with Our Thorough Guide</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-realme-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Realme Phone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mixing-made-easy-free-luts-bundle-includes-dji-miniair-2/"><u>Mixing Made Easy Free LUTS Bundle Includes DJI Mini/Air 2</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-this-article-introduces-one-of-the-best-movie-maker-for-mac-user-and-how-to-use-this-movie-maker-to-edit-video-footage-with-3-steps/"><u>New This Article Introduces One of the Best Movie Maker for Mac User and How to Use This Movie Maker to Edit Video Footage with 3 Steps</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/playing-mp4-on-dvd-players-can-it-be-done-unveiling-simple-fixes-for-you/"><u>Playing MP4 on DVD Players: Can It Be Done? Unveiling Simple Fixes for You!</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/ricodifica-mp2-nel-formato-wmv-senza-costo-su-internet-scopri-il-metodo-di-conversione-rapida-di-movavi/"><u>Ricodifica MP2 Nel Formato WMV Senza Costo Su Internet: Scopri Il Metodo Di Conversione Rapida Di Movavi</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/transformacion-de-dvd-en-hevch265-mp4-gratuita-como-mejorar-la-calidad-sin-gastos/"><u>Transformación De DVD en HEVC/H.265 MP4 Gratuita - Cómo Mejorar La Calidad Sin Gastos</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/usb-winx-mediatrans-ipadipodiphone/"><u>USBメモリ WinX MediaTrans: IPad・iPod・iPhoneへの変換ガイド</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/1725289258128-windows-10dvd/"><u>Windows 10環境下でのDVDバックアップに失敗する一般的な理由とそれを解消する手順</u></a></li>
</ul></div>

