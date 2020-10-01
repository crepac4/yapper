# yapper
Yet another scrapper.

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
![GitHub last commit](https://img.shields.io/github/last-commit/crepac4/yapper)

## Description

Layer of abstraction on top of puppeteer (headless chromium) covering the whole pipeline (extraction, processing, storage handling, archival).


#### In other words

An opinionated web scraping framework in nodejs on top of puppeteer which is a nodejs library used to control the chromium browser. The framework, basically automates a bunch of mundane tasks that are reapeted in almost every web scraping project and it makes it easier for me to extract, process, debug and finally archieve data from the web.

## Why?
Out of frustration for certain repeated tasks, and also some pain points regarding the debuggability of all sorts of weird obstucles on different websites.


## To be implemented
1) External (to chromium) downloader that seamlessly integrates with headless chromium.
2) zipping, categorizing and otherwise getting rid of uneeded data.

## Challenges
It might prove difficult to test for a library that is heavily dependent on a headless browser.




## What does 'yapper' mean?
Nothing. But it rhymes with yet another scrapper!


