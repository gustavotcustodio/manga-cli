# Manga-Cli
Download manga chapters through the terminal and read them using sxiv.

A cli (command line interface) to [mangabuddy](https://mangabuddy.com/).

This script will create a folder:

  - `./tile-name/chapter`

## Dependencies:
  - fzf  (Search Titles)
  - sxiv (Image View)
  - curl (Access mangabuddy content)

This project is based on [redyt](https://github.com/Bugswriter/redyt/blob/main/redyt) and [ani-cli](https://github.com/pystardust/ani-cli).

## Usage:
Execute this script and provide a manga title when asked for.

After providing the title, you select the chapters you wish to download.

  - `Available chapters (1-100): 1 5`

This will download chapters from 1 to 5.

```
Options:
- h    help text
- t    manga title
- n    do not open sxiv after downloading
```
