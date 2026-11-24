# KH Studio extensions

The source for each extension is public: `story-studio-video-generator`, `story-studio-image-generator` and `story-studio-audio-generator` (owner, 2026-11-23).

Each extension is an unpacked Chrome extension (Manifest V3). Download the zip from its release,
unzip it, then open `chrome://extensions`, turn on Developer mode, and choose **Load unpacked**.

`extensions.json` is the index the Studio Launcher KH reads: name, version, one-line summary,
download URL, sha256 and byte count. A download is only trusted when its sha256 matches the index.
Each row may also carry `icon` and `screenshot` — plain https URLs used to draw the Launcher tile.

Those image URLs track `main` **unpinned, by choice**: they are display, not artifacts, so an icon or
screenshot can change under a published row without making a row wrong. Freeze one by using a commit
sha in the path if that ever matters.
