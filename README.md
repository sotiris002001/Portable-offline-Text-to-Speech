# Portable eSpeak NG for Linux

A portable, offline Text-to-Speech (TTS) package for Linux based on
[eSpeak NG](https://github.com/espeak-ng/espeak-ng).

The project bundles eSpeak NG, its speech and language data, and a local
`aplay` binary with ALSA support into a single directory.

The goal is simple: **copy the folder to another Linux machine and use
Text-to-Speech without installing eSpeak NG, Python, or other application-level
dependencies.**

## Features

-  Offline Text-to-Speech
-  Multiple languages, including Greek
-  Self-contained application directory
-  Designed for Linux
-  No Python required
-  No system-wide eSpeak NG installation required
-  No system-wide `aplay` installation required
-  Automatically generates a WAV file
-  WAV output is stored next to `speak.sh`
-  Suitable for USB drives, external SSDs and portable projects
-  Can be integrated into other shell scripts

## Basic usage

```bash
chmod +x speak.sh
./speak.sh -v el "Hello World"
