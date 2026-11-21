# KH Studio extensions

Downloads only — the source for each extension stays private.

Each extension is an unpacked Chrome extension (Manifest V3). Download the zip from its release,
unzip it, then open `chrome://extensions`, turn on Developer mode, and choose **Load unpacked**.

`extensions.json` is the index the Studio Launcher KH reads: name, version, one-line summary,
download URL, sha256 and byte count. A download is only trusted when its sha256 matches the index.
