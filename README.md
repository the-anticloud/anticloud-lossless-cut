# LOSSLESS_CUT

> LosslessCut The swiss army knife of lossless video/audio editing

**Category:** MOVIES_MEDIA · **Ecosystem:** unknown · **Vendored upstream:** https://github.com/mifi/lossless-cut · **Pinned commit:** `2610158c7861e0b96e2020cebcdd3c539ff33830` · **Vendor:** Anticloud FZ LLE

## What This Project Is

LosslessCut The swiss army knife of lossless video/audio editing

This is the upstream project, vendored at the pinned commit above and packaged offline-first. The 12 improvements Anticloud adds live in `anticloud/` and are described under *Anticloud Overlay* below. Every fact in this file traces to a file in this directory.

## Installation

```
# See the upstream README (linked above) for build steps.
```

## Usage

- Cut out commercials from a recorded TV show (and re-format from TS to MP4).
- Remove audio tracks from a file.
- Extract music track from a video and cut it to your needs.
- Add music to a video (or replace existing audio track).
- Combine audio and video tracks from separate recordings.
- Include an external subtitle into a video
- Quickly change a H264/H265 MKV video to MOV or MP4 for playback on iPhone.
- Import a list of cut times from other tool as a EDL (edit decision list, CSV) and run these cuts with LosslessCut.
- Export a list of cut times as a CSV EDL and process these in another tool.
- Quickly cut a file by its MP4/MKV chapters.
- Quickly cut a [YouTube video](https://youtube-dl.org/) by its chapters (or music times from a comment).
- Change the language of a file's audio/subtitle tracks.
- Attach cover art / thumbnail to videos / audio from an external JPEG file or from a frame on the timeline.
- Change author, title, GPS position, recording time of a video.
- Fix rotation of a video that has the wrong orientation flag set.
- Loop a video / audio clip X times quickly without re-encoding, see [#284](https://github.com/mifi/lossless-cut/issues/284).
- Convert a video or parts of it into X image files (not lossless)
- Losslessly split a video into one file per scene (note you probably have to shift segments, see [#330](https://github.com/mifi/lossless-cut/issues/330).)
- Cut away silent parts from an audio/video file.
- Split video into segments to for example respect Twitter's 140 second limit.
- Annotate each segment with one or more tags, then use those tags to organize your segments or use it to create an output folder structure or hierarchy for your segments.

See also [Recipe cookbook](docs/recipes.md)

## Anticloud Overlay

The 12 improvements live under `anticloud/`. Run the check suite from this directory:

```
python anticloud/bench/runner.py --cwd anticloud
```

## Benchmark Results

The suite is recorded in `BENCH.json`; no benchmark rows were found in this package.

## Licence

The upstream licence is preserved in `LICENSE` and `THIRD_PARTY_LICENSES/`. The Anticloud overlay is licensed under Anticommons 0.1.0 (`ANTICOMMONS_LICENSE.md`).

## Verification

SHA3-256 of `BENCH.json`:

```
333c0d1a0d9d0ad60ec453c096a64ddb532ae1c2f3878e43e385c4d7f1e78360
```

Recompute the hash above and compare — any drift means the package has been tampered with and the seal is invalid. This is a self-assessment; no external audit has been performed and a SOC 2 / NIST independent audit is committed post-funding.
