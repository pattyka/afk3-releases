# AFK releases

This repository holds only the signed release artifacts for AFK (the macOS agent app, AFK Agent, and its dictation tools), published as GitHub Releases; it contains no source code. You do not download anything here by hand: the AFK iPhone app shows you a one-line command such as `curl -fsSL https://afk3-get.web.app/i | sh -s <CODE>`, and that installer fetches the release listed in [manifest.json](https://afk3-get.web.app/manifest.json) and checks every file's sha256 and code signature before installing it.
