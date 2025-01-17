<!-- PROJECT LOGO -->
<br>
<div align="center">
  <a href="https://github.com/andros21/ytdl-mpv">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/58751603/167302289-d70b18ab-c91c-499b-bbbd-57f884d58089.png">
      <img src="https://user-images.githubusercontent.com/58751603/127172656-40c7adf1-b6de-4985-a1c0-14a2e58dc6f3.png" alt="Logo" width="470">
    </picture>
  </a>
<br>
  <a href="https://github.com/andros21/ytdl-mpv/actions/workflows/lint.yml">
    <img src="https://img.shields.io/github/actions/workflow/status/andros21/ytdl-mpv/lint.yml?branch=master&label=Lint%20CI&logo=github&style=flat-square" alt="Lint CI">
  </a>
   <a href="https://github.com/davatorium/rofi">
    <img src="https://img.shields.io/badge/rofi-interface-important?logo=youtube&style=flat-square" alt="rofi">
  </a>
  <a href="https://github.com/andros21/ytdl-mpv/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/andros21/ytdl-mpv?color=blue&label=License&style=flat-square" alt="License">
  </a>
  <h4 align="center">Rofi script to browse and play YouTube contents <br>using <a href="https://github.com/yt-dlp/yt-dlp/">yt-dlp</a> and <a href="https://github.com/mpv-player/mpv">mpv</a></h4>
  <div align="center">
    <a href="#star-features">Features</a>
    ·
    <a href="#rocket-setup">Usage</a>
    ·
    <a href="#runner-run">Run</a>
  </div>
  <br>
   <img src="https://user-images.githubusercontent.com/58751603/191463905-c7154c4b-9f4c-460b-85c1-7c5cdbb74d1c.gif" alt="Demo" width="570">
</div>

## :star: Features

* Search history and yt query cache
* Customize script using available flags
* Simple and intuitive rofi menu
  * Play video, audio
  * Append to playlist
  * Loop playlist
  * Edit current playlist
  * Save/Load current playlist
  * Help for key bindings
  * ...

## :rocket: Setup

**Dependencies**

* `nc` `sqlite3` `xargs`
* [`mpv`](https://github.com/mpv-player/mpv)
* [`rofi>=1.6.1`](https://github.com/davatorium/rofi)
* [`yt-dlp==2023.02.17`](https://github.com/yt-dlp/yt-dlp)

**Opt dependencies**

* `xclip` for copy yt video id in clipboard

**Install**

Simply make it

```
git clone https://github.com/andros21/ytdl-mpv
cd ytdl-mpv
make install
```

## :runner: Run

Is advisable to key bind `ytdl-mpv`, so that rofi menu can be opened wherever you are!\
For **debugging purposes**, instead, could be useful run `ytdl-mpv` inside a shell to view stdout/stderr
