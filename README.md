# LOSSLESS_CUT

> Anticloud offline package — upstream: mifi/lossless-cut @ `master`.

## What This Project Does

The swiss army knife of lossless video/audio editing

**Topics:** codec, cut, editor, ffmpeg, lossless, losslesscut, player, video, video-editor, video-files

## Upstream README

<div align="center">
	<br>
  <p><a href="https://losslesscut.app/"><img src="src/renderer/src/icon.svg" width="120" alt="LosslessCut" /></a></p>
  <p><a href="https://losslesscut.app/"><b>LosslessCut</b></a></p>
  The swiss army knife of lossless video/audio editing
	<br>
  <img src="https://github.com/mifi/lossless-cut/workflows/Build/release/badge.svg" />
  <a href="https://paypal.me/mifino/usd"><img src="https://img.shields.io/badge/Donate-PayPal-green.svg" /></a> <a href="https://github.com/mifi/lossless-cut#download"><img src="https://img.shields.io/github/v/release/mifi/lossless-cut" /></a> <a href="https://discord.gg/fhnEREfUJ3"><img src="https://img.shields.io/discord/986051448385183804" /></a> <a href="https://twitter.com/losslesscut"><img src="https://img.shields.io/twitter/follow/losslesscut?label=Twitter&style=social" alt="Twitter"></a>
	<br>
	<br>
  <a href="https://mifi.no/thanks/">Thanks to my supporters</a> and everyone who purchased LosslessCut!
	<br>
	<br>
  <p align="center"><img src="main_screenshot.jpg" width="600" alt="screenshot" /></p>
	<br>
	<br>
</div>

LosslessCut aims to be the ultimate cross platform FFmpeg GUI for extremely fast and lossless operations on video, audio, subtitle and other related media files.
The main feature is lossless trimming and cutting of video and audio files, which is great for saving space by rough-cutting your large video files taken from a video camera, GoPro, drone, etc. It lets you quickly extract the good parts from your videos and discard many gigabytes of data without doing a slow re-encode and thereby losing quality. There are also many more [use cases](#typical-workflow). Everything is extremely fast because it does an almost direct data copy, fueled by the awesome FFmpeg which does all the grunt work.

## Table of contents

- [Features](#features)
- [Example lossless use cases](#example-lossless-use-cases)
- [Download](#download)
- [Supported formats](#supported-formats)
- [Documentation, usage & getting started](#documentation)
- [Video demos](#video-demos)
- [Featured](#featured)
- [Attributions](#attributions)

## Features

- Lossless cutting of most video and audio formats
- [Smart cut](https://github.com/mifi/lossless-cut/issues/126) (experimental)
- Losslessly cut out parts of video/audio (for cutting away commercials etc.)
- Losslessly rearrange the order of video/audio segments
- Lossless merge/concatenation of arbitrary files (with identical codecs parameters, e.g. from the same camera)
- Lossless multi track/stream editing
  - Combine arbitrary tracks from multiple files (ex. add music or subtitle track to a video file)
  - Remove unneeded tracks
  - Replace or re-encode only some tracks
  - Extract all tracks from a file (extract video, audio, subtitle, attachments and other tracks from one file into separate files)
- View technical data about all tracks. Edit file metadata, per-track metadata and per-track disposition
- Select video/audio tracks for playback. Playback mu

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
