TypeWords Japanese audio pack

7000 bundled MP3 recordings: kana, built-in N3 vocabulary, example sentences,
collocations, related expressions and short articles (2026-11-21 snapshot).
Generated with pyopenjtalk-plus 0.4.1.post10 / Open JTalk, HTS Voice "Mei".
Voice: Copyright (c) 2009-2013 Nagoya Institute of Technology,
Department of Computer Science. Released by the MMDAgent Project Team.
Voice license: Creative Commons Attribution 3.0.
https://creativecommons.org/licenses/by/3.0/
https://github.com/tsukumijima/pyopenjtalk-plus
https://open-jtalk.sourceforge.net/
See LICENSE-Mei.txt for the original voice notice.

Recordings are synthetic speech, encoded as 64 kbps mono MP3 at 0.9 synthesis speed.
They are learning aids; synthetic pitch/accent may differ from natural speech.
The text includes project content and user-supplied wordbooks; the voice license
does not grant additional rights to the source text.
recordings.json maps Japanese text/readings to MP3 filenames.
The app manifest uses text + a NUL separator + reading for homographs.
All audio files can be served as ordinary static resources; no TTS engine or
system voice installation is required to play this pack.

To extend the pack after updating built-in wordbooks, first run
node --experimental-strip-types scripts/japanese-audio-manifest.mjs,
then scripts/generate-japanese-audio.py with the cached Python tools available.
The staging plan is in output/audio/japanese. Generation is incremental and the
active manifest changes only after every planned recording has been verified.
Web browsers may require tapping the pronunciation button before automatic audio.
Unrecorded content uses a device Japanese voice when available; otherwise it is
sent to Youdao's Japanese pronunciation service for immediate online playback.
The app does not save or export these online responses. Network access is needed.
The downloadable source archive omits generated MP3 binaries to keep it compact;
it includes the recording list, generation scripts and voice license. The actual
MP3 files are distributed as static resources alongside the website.
