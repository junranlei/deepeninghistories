# Deepening Histories of Place Archive

This repository contains a static web archive of the Deepening Histories of Place, using WACZ (Web Archive Collection Zipped) technology and ReplayWeb.page for hosting and playback.

## Overview

This archive preserves the Deepening Histories of Place website in a self-contained format that can be viewed offline or hosted as static files.

## Technical Details

- **Archive Format**: WACZ (Web Archive Collection Zipped)
- **Playback Technology**: [ReplayWeb.page](https://replayweb.page/)
- **Archive Location**: `./wacz/deepening.wacz`

## How It Works

The archive is created using [Browsertrix Crawler](https://github.com/webrecorder/browsertrix-crawler), a high-fidelity browser-based web crawler designed specifically for web archiving. The crawler captures all the necessary resources (HTML, CSS, JavaScript, images, etc.) and packages them into a WACZ file.

The ReplayWeb.page web component is then used to replay the archived content directly in the browser, providing a seamless viewing experience of the archived website.


## Tools Used

- **[Browsertrix Crawler](https://github.com/webrecorder/browsertrix-crawler)** - For crawling and creating the WACZ archive
- **[ReplayWeb.page](https://replayweb.page/)** - For rendering the archived content in the browser

## More Information

For more information about the tools used:
- [Browsertrix Crawler Documentation](https://crawler.docs.browsertrix.com/user-guide/)
- [WACZ Format](https://github.com/webrecorder/wacz-format)
- [ReplayWeb.page Documentation](https://replayweb.page/docs)