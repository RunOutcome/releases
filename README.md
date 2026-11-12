# Outcome releases

Release downloads for `out`, the Outcome CLI and server in one binary.
This repository holds releases only. It has no source code.

## Install

macOS (Homebrew):

    brew install runoutcome/tap/out

macOS and Linux, from a release:

    curl -fsSL https://github.com/RunOutcome/releases/releases/latest/download/install.sh | sh

Windows: download `out-<version>-windows-amd64.zip` from the latest release.

## Verify

Every release has `checksums.txt` (SHA-256 of each file) and `checksums.txt.sig`,
an Ed25519 signature over it. `out upgrade` checks both before replacing itself.

## Channels

A plain `vX.Y.Z` tag is a stable release. A tag with a suffix (`v0.1.0-rc.1`) is a
pre-release and is offered only on the beta channel.

## Support

https://runoutcome.com
