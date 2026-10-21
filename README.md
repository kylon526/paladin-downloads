# Paladin downloads

Public download information for Paladin on Apple Silicon Macs running macOS 15 or later.

[Download page](https://kylon526.github.io/paladin-downloads/) · [Earlier releases and checksums](https://github.com/kylon526/paladin-downloads/releases)

The fully renamed Paladin candidate has not been published here yet. It creates a separate, empty installation and does not import previous rules or protector credentials. Earlier releases remain archived with their original filenames and signed bundle contents and require an existing configured installation. Follow the instructions for the version you download. Remove previous protection through its own controls before configuring Paladin on the same connection.

The repository rename does not upgrade archived installers or an installed app.

The Paladin candidate bundles its desktop app, menu monitor, CLI, gateway and
Python runtime. Copying the app does not activate protection. Opening the installed
candidate starts the menu monitor; first-run setup configures protection separately.
Closing the desktop leaves the independent monitor and protection running.

Builds are locally signed and are not Apple-notarized. If macOS blocks first open,
use System Settings → Privacy & Security → Open Anyway for the downloaded app.
[Apple's instructions](https://support.apple.com/en-us/102445).

Rules, protector credentials, certificates, logs and network settings are never
included in public downloads. Source is private; this repository holds download
information and release assets.
