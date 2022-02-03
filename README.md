<h1 align="center">FLIX-CLI</h1>
<p align="center">f@#k netflix use flix-cli a tool which search magnet links and stream it with peerflix</p>
<h2 align="center">
[![GitHub Actions CI Status](https://github.com/DemonicAayush/flix-cli/workflows/GitHub%20Actions%20CI/badge.svg)](https://github.com/DemonicAayush/flix-cli/actions)

[![Coverity Status](https://scan.coverity.com/projects/5494/badge.svg)](https://scan.coverity.com/projects/5494)
 </h2>

### How does this work?

This is a shell script. It scrapes 1337x and gets the magnet link.
After this it uses [peerflix](https://github.com/mafintosh/peerflix) to stream the video from the magnet link.
For scraping, the script uses simple gnu utils like sed, awk, paste, cut.

## Requirements

* [peerflix](https://github.com/mafintosh/peerflix) - A tool to stream torrent. `sudo npm install peerflix -g`

## Installation

### cURL
cURL **flix-cli** to your **$PATH** and give execute permission.

```sh
$ sudo curl -sL "https://raw.githubusercontent.com/DemonicAayush/flix-cli/master/flix-cli" -o /usr/local/bin/flix-cli
$ sudo chmod +x /usr/local/bin/flix-cli 
```

- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply remove `flix-cli` from your **$PATH**, for example `sudo rm -f /usr/local/bin/flix-cli`.

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

