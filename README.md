# Workover Write for Mac: update channel

Release files only, published by CI from scalemath/workover (`.github/workflows/write-desktop.yml`).
The app reads `latest.json` from https://scalemath.github.io/workover-write-updates/ and checks each
update bundle's signature against its own public key before installing it. Nothing here is edited by
hand; each publish replaces the branch with one fresh commit.
