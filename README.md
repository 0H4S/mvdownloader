<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/0H4S/mvdownloader@main/icon.svg" alt="MV Downloader Icon" width="100" height="100">
  <h1>MV Downloader</h1>
  <a href="https://greasyfork.org/scripts/600127" target="_blank"><img alt="Greasy Fork Version" src="https://img.shields.io/greasyfork/v/600127?style=for-the-badge&label=version&color=%23EFBF04"></a>
  <a href="https://greasyfork.org/scripts/600127" target="_blank"><img alt="Greasy Fork Downloads" src="https://img.shields.io/greasyfork/dt/600127?style=for-the-badge&label=downloads"></a>
  <a href="#"><img src="https://img.shields.io/badge/license-All%20Rights%20Reserved-red?style=for-the-badge" alt="License All Rights Reserved"></a>
  <p><sub>Made with ❤️ by <a href="https://github.com/0H4S">OHAS</a></sub></p>
</div>

<hr>

<div align="center">
  <p><b>Your favorite videos and audio, saved to your computer in just a few clicks.</b></p>
  <p><b>MV Downloader</b> makes it easy to download videos and audio while you browse. Choose your content, select the format and quality, and send the download request to the companion application on your computer.</p>
  <p>You can download content one item at a time or collect links in <b>playlists</b> to download later, all through an interface integrated into the pages you visit.</p>
</div>

<hr>

## What You Can Do

- **Download videos or audio only:** choose what you want to save for each download.
- **Choose the format:** MP4 or MKV for videos; MP3 or WAV for audio.
- **Adjust the quality:** videos in 360p, 480p, 720p, 1080p, or up to 4K; audio with 128, 192, or 320 kbps options.
- **Create your own playlists:** collect content from different pages into playlists with custom names and icons.
- **Download in batches:** send every item in a playlist for download without having to reopen each page.
- **Organize before downloading:** edit titles, modify playlist items, and remove anything you no longer need.
- **Use links from other websites:** paste the content URL into the panel opened by the floating button.
- **Personalize your experience:** choose the theme, language, and which buttons you want to display on pages.

Available quality options depend on the original content and the selected format. Selecting 4K, for example, does not upscale a lower-resolution video to 4K.

## Where It Works

MV Downloader provides download buttons alongside videos on the following platforms:

**YouTube, X/Twitter, Instagram, Bilibili, Facebook, TikTok, Reddit, Threads, and Pinterest.**

On other websites, use the floating button and paste the content link. Whether the download works depends on whether the website and content are supported by the companion application.

## What You Need

1. **A computer with a compatible browser.** See the table below.
2. **An installed UserScript manager.** This is the browser extension that allows MV Downloader to run in your browser.
3. **The MV Downloader UserScript installed and enabled.**
4. **The MV Downloader companion application installed and running on the same computer.** It handles downloads and conversions.
5. **An internet connection and enough available storage space to save your files.**

> **The companion application is required.** To download content, keep it running and paired with the UserScript. Installing only the UserScript in your browser is not enough.

## Compatibility

### UserScript Managers

| Manager | Compatible |
| --- | :---: |
| Tampermonkey | ✅ |
| Violentmonkey | ✅ |
| ScriptCat | ✅ |

### Browsers

| Browser | Compatible |
| --- | :---: |
| Google Chrome | ✅ |
| Microsoft Edge | ✅ |
| Brave | ✅ |
| Mozilla Firefox | ✅ |
| Opera | ✅ |

Use one of the compatible UserScript managers available for your browser, and keep your browser, extension, and MV Downloader up to date.

## How to Install and Set Up

1. Install one of the compatible UserScript managers in your browser.
2. Open the MV Downloader installation page and confirm the installation in your UserScript manager.
3. Install and launch the MV Downloader companion application on your computer.
4. In the UserScript settings, go to the **connection** section.
5. Enter the **port** and **pairing key** provided by the companion application, then select the pairing option.
6. Use the connection verification option to confirm that everything is ready.

Your pairing information is saved for future use. Keep the companion application running whenever you want to download content.

## How to Use

### Download a Video or Audio

1. Open one of the integrated platforms and navigate to the video you want.
2. Click the MV Downloader download button next to the video.
3. Choose **Video** or **Audio**.
4. Select the format and quality. You can also customize the title if you want.
5. Click **Download**. The companion application will receive the request and handle the download.

### Download Using a Link

1. On a website without direct integration, click the MV Downloader floating button.
2. Paste the link to the content you want to download.
3. Choose the media type, format, and quality.
4. Click **Download**.

### Collect Content in a Playlist

1. Open the MV Downloader panel for the content you want.
2. Go to **Playlists** and create a new playlist or select an existing one.
3. Add the content to the playlist and repeat for any other content you want to save.
4. When you're ready, open the playlist and download an individual item or send the entire playlist for download.

You can also access your playlists through the MV Downloader menu in your UserScript manager.

## Frequently Asked Questions

### The download button isn't showing up. What should I do?

Make sure the UserScript is enabled and that your UserScript manager has permission to run on that website. In the MV Downloader preferences, check that the option to display download buttons is enabled. Then reload the page and open the video.

### The application isn't connected.

Launch the companion application on the same computer and use the connection verification option in the UserScript settings. If necessary, double-check your pairing information.

### Can I close the companion application?

It must remain running to handle downloads. Open it again before submitting any new download requests.

### Does it work on every website?

MV Downloader integrates with several platforms and also lets you attempt downloads using links from other websites. Availability depends on the website, the content, and the companion application's support.

### Are There Ads?

Yes. MV Downloader includes advertisements and offers an ad-free access option.

## Usage Policies

- Only download content you own or have permission or another valid legal right to download.
- Respect creators' rights, website terms of service, and applicable laws.
- The availability of a link or download button does not grant you rights to the content or permission to redistribute it.
- Use of MV Downloader must comply with the terms and authorizations established by OHAS. The product's presentation and availability do not replace these authorizations.

## Credits and Licenses

### Download Engines

The MV Downloader companion application uses **[yt-dlp](https://github.com/yt-dlp/yt-dlp)** as its primary engine for video and audio downloads. If it cannot complete a download, the application tries alternative engines, including **[Streamlink](https://github.com/streamlink/streamlink)** and **[You-Get](https://github.com/soimort/you-get)**. Support for individual websites and content depends on the available engines.

You can also add compatible external engines that support the yt-dlp command-line interface. We thank the authors and contributors of the projects used.

Each engine is governed by its own license:

- **yt-dlp:** the original code is released under **[The Unlicense](https://github.com/yt-dlp/yt-dlp/blob/master/LICENSE)**. Some distributed builds include components governed by other licenses; see the [official licensing information](https://github.com/yt-dlp/yt-dlp#licensing).
- **Streamlink:** released under the **[2-Clause BSD License](https://github.com/streamlink/streamlink/blob/master/LICENSE)**.
- **You-Get:** released under the **[MIT License](https://github.com/soimort/you-get/blob/develop/LICENSE.txt)**.

### Application and UserScript

The original material associated with the MV Downloader application and UserScript is subject to **OHAS's proprietary license, with all rights reserved**, as specified in the [full license text](https://github.com/0H4S/mvdownloader/blob/main/license).

This license is separate from the licenses governing the download engines and other third-party components. The permissions granted by those projects do not automatically extend to OHAS's original material.

Under the provided license, the use, execution, copying, modification, reuse, and redistribution of OHAS's protected material require prior, express, written authorization, except where rights or permissions apply by law. Publishing the material or making it freely accessible does not, by itself, grant such authorization.

Third-party components remain subject to their respective licenses. This README introduces the product and summarizes these terms; it does not replace the full licenses or grant any additional permissions.