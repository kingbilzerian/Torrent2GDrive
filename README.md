**Best way to do cloud torrenting.**

# Torrent & URLs To Google Drive Downloader
Simple notebook to stream torrent files to Google Drive using Google Colab.

<p align="center">
	
**Torrent** <br>
<a href="https://colab.research.google.com/github/JeelPatel231/Torrent2GDrive/blob/master/Torrent_To_Google_Drive_Downloader.ipynb" target="_parent"><img src="http://icons.iconarchive.com/icons/shaunkleyn/phlat-blue-folders/128/Torrents-icon.png" alt="Torrent/Open In Colab"/></a>

**URLs** <br>
<a href="https://colab.research.google.com/github/JeelPatel231/Torrent2GDrive/blob/master/GDrive_Streaming.ipynb" target="_parent"><img src="http://icons.iconarchive.com/icons/dtafalonso/android-lollipop/128/Downloads-icon.png" alt="URLs/Open In Colab"/></a>

</p>
### Tutorial
1. Click the badge which says 'Open in Colab'.
2. Goto **File > Save a copy in Drive...** (a new tab opens with the copy of this notebook).
3. Run the whole notebook (**Runtime > Run all**).
4. Follow directions there.

After download finishes the downloaded files will be in there in your drive in a folder named "***Torrent***".

### What is the purpose of it?
1. Because of Google Servers speed, I downloaded 35GB of file and the average speed was 60MBPS.
2. Because it is in the cloud, by that I mean I can access it anywhere on my phone, tablet or etc without copying file to all of them.
3. You can bypass any restrictions on torrenting set by your ISP and access your files through drive (neat isn't it!).

### Frequently Asked Questions
1. **How get more disk space**: We can now download bigger torrents. To do it

	> Go to Runtime -> Change Runtime and give GPU as the Hardware Accelerator.  
You will get around 384GB to download any torrent you want.
But this file won't be uploaded to your drive until you have that much space in drive it'll stay in colab's disk.

2. **Downloading missing files without re-downloading whole torrent**: If somehow some files are missing try to re-download torrent (just by re-running the cell). Fastresume will check files.






# This whole repo is against Google Colab policy and you shouldn't be using it.
> **Why are hardware resources such as T4 GPUs not available to me?**
The best available hardware is prioritized for users who use Colaboratory interactively rather than for long-running computations. Users who use Colaboratory for long-running computations may be temporarily restricted in the type of hardware made available to them, and/or the duration that the hardware can be used for. We encourage users with high computational needs to use Colaboratory’s UI with a local runtime.
Please note that using Colaboratory for cryptocurrency mining is disallowed entirely, and may result in being banned from using Colab altogether.

<sub>Source: https://research.google.com/colaboratory/faq.html</sub>

