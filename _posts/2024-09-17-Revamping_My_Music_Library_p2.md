---
layout: post
title:  "Revamping My Music Library - p2 Synching Traktor DJ Pro with Android"
date:   2024-09-17
tags: [music, tech]
---

After recently migrating my music collection to Traktor DJ, I embarked on a mission to seamlessly sync it to my Android phone for offline and mobile listening. Here's how I achieved this, step by step.

**Exporting Playlists from Traktor DJ**

The first step was finding a way to regularly export playlists from Traktor DJ, which doesn't natively support this feature. After some research, I discovered a script on [GitHub](https://github.com/lord-carlos/traktor-2-playlist) that could do the job (big thanks to [lord-carlos](https://github.com/lord-carlos) for the initial work on the script). I contributed a few modifications to tailor it to my specific needs, ensuring it could handle my library's structure and export formats.

An unexpected benefit of this script is that I can now play all my playlists using any music app that supports standard playlist formats:
![Music Player](/images/musicPlayer.png)

**The Synchronization Solution: Enter Syncthing**

With the playlists exported, the next step was to push these playlists, together with music files to my phone. For this, I turned to [Syncthing](https://syncthing.net/), an open-source file synchronization tool.

**Quick Syncthing Introduction**

Syncthing is a free, decentralized file synchronization application that works across various platforms. It allows you to keep folders synced between multiple devices without relying on a central server. Here's why it's great for this setup:
- Real-time synchronization
- End-to-end encryption
- No size limits or restrictions
- Works on both desktop and mobile devices

**Finding the Right Android Music Player**

After trying several Android music players, I found that [Vinyl](https://github.com/VinylMusicPlayer/VinylMusicPlayer?tab=readme-ov-file) was the perfect match for my setup. It seamlessly imports the synced playlists without requiring any manual edits, making it a hassle-free solution for enjoying my Traktor DJ library on Android.

**Streamlining the Process**

To make the entire sync process as smooth as possible, I created a second script that:
1. Clears the folder where I store playlist
2. Runs the first script to export fresh playlists from Traktor DJ
3. Launches Syncthing on my computer

With this automation in place, all I need to do is:
1. Run the second script on my computer
2. Launch Syncthing on my Android device and wait for the changes to sync

And voilà! My entire Traktor DJ library, complete with up-to-date playlists, is ready for on-the-go listening.
Traktor on the left and Vinyl on Android on the right:
![Traktor and Vinyl](/images/traktorAndVinyl.png)

**Conclusion**

This setup has revolutionized how I interact with my music library. Not only can I manage and organize my tracks professionally in Traktor DJ, but I can also enjoy my entire collection on my phone with minimal effort.

You can check out the <a href="{{ site.url }}/blog/revamping-my-music-library">first part of my music library revamp series</a>, where I detailed my process of migrating from iTunes to Traktor DJ.