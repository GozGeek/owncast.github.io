---
title: "Watching an Owncast Stream on Televisions"
description: "The web isn't the only option for watching an Owncast stream."
tags: ["watching", "tv", "television", "chromecast", "vlc", "casting", "kodi"]
---

{{< alert icon="💡" text="This document is a work in progress. Please submit any applications or methods that work for you." >}}

There are numerous ways for you to watch an Owncast live stream on many
different devices. On this page we'll try to share some.

**Note:** None of the applications listed on this page are provided by, endorsed by, or supported by Owncast. You should make your own choices about what applications you choose to install. Products listed here are simply suggestions that have been tested and found to work with Owncast.

## Watching on your Television

Any application that supports HLS video will play back an Owncast stream. Install any video playback application for your platform of choice, and put in the URL `https://owncast.server/hls/stream.m3u8` to access the stream directly.

### Chromecast

[Visit the official Chromecast documentation](https://support.google.com/chromecast/answer/3228332).

1. On your computer, open Chrome.
1. Visit the Owncast server you want to watch.
1. At the top right, click the More button and then Cast.
1. Choose the Chromecast device where you want to watch the content.
1. If you're already using the Chromecast, your content will replace what's on your TV.

### AppleTV

VLC for tvOS

1. Install [VLC](https://www.videolan.org/vlc/download-appletv.html) from the tvOS App Store.
1. Visit the "Network Stream" tab.
1. Select the text input field.
1. Type the server you wish to watch. For example: `https://watch.owncast.online`
1. Select it from the list.

AirPlay

[Visit Apple's AirPlay documentation](https://support.apple.com/en-us/HT204289)

1. Open the Owncast stream you want to watch on your iPhone or Mac computer.
1. Play the Owncast stream.
1. Press the _AirPlay_ button.
1. Select your AppleTV.

### Amazon Fire TV

1. Install [VLC for Amazon Fire TV](https://www.amazon.com/VLC-Mobile-Team-for-Fire/dp/B00U65KQMQ) from the Amazon App Store.
1. Select "Streams" from the "Browsing" section.
1. Type in the name of the stream you wish to watch. For example: `https://watch.owncast.online`.
1. Select "Next".

### Google TV

1. Install VLC from the Google Play store.
1. Select "Streams" from the "Browsing" section.
1. Type in the name of the stream you wish to watch. For example: `https://watch.owncast.online`.
1. Select "Next".

### Roku

AirPlay

[Visit Apple's AirPlay documentation](https://support.apple.com/en-us/HT204289)

1. Open the Owncast stream you want to watch on your iPhone or Mac computer.
1. Play the Owncast stream.
1. Press the _AirPlay_ button.
1. Select your Roku.

### LG TVs (WebOS)

### Samsung TVs

## Browsing the Owncast Directory on your TV

Almost any application that supports adding _IPTV_ or _M3U_ playlists can support the directory.
Choose an application, and add `https://directory.owncast.online/api/iptv` as your playlist URL.

### AppleTV

1. Install [iPlayTV](https://apps.apple.com/us/app/iplaytv-iptv-m3u-player/id1072226801) from the tvOS App Store.
1. Visit Settings -> Edit
1. For the `M3U` Playlist URL: `https://directory.owncast.online/api/iptv`
1. Change the `Channels Refresh` to the lowest value it offers.

### Kodi

- Install the [Owncast Kodi Plugin](https://github.com/rAcHekLoS/plugin.video.owncast) by rAcHekLoS.

### Roku

- Install the [Owncast Directory App](https://channelstore.roku.com/details/7419f1032ebbfe1c7dcc6e2f3f5c8767/owncast)
- Browse, or search for the stream name you wish to watch.

### LG TVs (WebOS and possibly other smart TVs)

1. Install **SATV** (free) from your smart TV's app store.
1. Run it and press button to **"Add Playlist"**.
1. Type in: `https://directory.owncast.online/api/iptv`. Make sure it's _https_.
1. Double check you typed it in correctly.
1. Save this playlist.
1. It will refresh the current live streams each time you launch the SATV app.
1. Choose the live stream you want to watch.
