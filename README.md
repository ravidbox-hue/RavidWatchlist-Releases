# MY Watchlist — Android TV releases

Public APK distribution for MY Watchlist, an Android TV watchlist manager.

This repository contains distribution documentation, version metadata and GitHub Release assets only. Application source remains private.

Download APKs from [Releases](https://github.com/ravidbox-hue/RavidWatchlist-Releases/releases). The update manifest is [latest.json](latest.json). Releases include the APK, SHA256SUMS.txt and their exact latest.json.

Install the bootstrap updater build over the existing app without uninstalling. Preserve package com.ravid.watchlist and the same signing identity. Subsequent compatible versions can update from Settings. Updates are optional; Android requires normal installation permission and confirmation.

The current APK uses the existing Android debug certificate. Release-optimized signing has not been configured. Certificate SHA-256:

7d3ad07299825e0fa82af883aad5478e9792422340604d920a53d4c0b0cdf256

Never upload application source, keystores, credentials or private build logs here. GitHub-generated source archives contain only this distribution repository's documents/manifest.