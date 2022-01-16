<h1 align="center">FLIX-CLI</h1>
<p align="center">f@#k netflix use flix-cli a tool which search magnet links and stream it with webtorrent</p>

##
<p align="center">
<img src="https://github.com/Bugswriter/notflix/blob/master/preview.gif" alt="Video Preview" width="500px">
</p>

### How does this work?

This is a shell script. It scrapes 1337x and gets the magnet link.
After this it uses [webtorrent](https://webtorrent.io/) to stream the video from the magnet link.
For scraping, the script uses simple gnu utils like sed, awk, paste, cut.

## Requirements

* [webtorrent](https://webtorrent.io/) - A tool to stream torrent. `npm install webtorrent-cli -g`

## Installation

### cURL
cURL **flix-cli** to yout **$PATH** and give execute permission.

#### Linux

```sh
$ sudo curl -sL "https://raw.githubusercontent.com/flix-cli/flix-cli/master/flix-cli" -o /usr/local/bin/flix-cli
$ sudo chmod +x /usr/local/bin/flix-cli 
```
#### Mac

```sh
$ sudo curl -sL "https://raw.githubusercontent.com/flix-cli/flix-cli/master/flix-cli-mac" -o /usr/local/bin/flic-cli-mac
$ sudo chmod +x /usr/local/bin/flix-cli-mac
```

- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply remove `flix-cli` from your **$PATH**, for example `sudo rm -f /usr/local/bin/flix-cli'.

## License
his project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

