# Wayback Save

Wayback Save is simple command-line utility save URLs to the Wayback Machine.

### Prerequisites

Wayback Save requires [Python 3](https://www.python.org/), [Selenium for Python 3](http://docs.seleniumhq.org/), and [geckodriver](https://github.com/mozilla/geckodriver).

On macOS, these can be installed easily with [Homebrew](https://brew.sh/) using the following commands:
```
brew install python3 geckodriver
pip3 install selenium
```

### Usage

The usage is simply:
```
wayback-save URL [URL...]
```

### For Many Pages

This script is very slow and is only practical for a very small number of web pages. If you wish to archive full websites then [Archive Team's ArchiveBot](https://www.archiveteam.org/index.php?title=ArchiveBot) is a more practical solution for you. It can crawl websites with up to a few hundred thousand urls.
