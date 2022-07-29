# Checksum.workflow

Checksum.workflow facilitates the display and verification of various checksums within Finder on macOS.

Checksum.workflow supports the following cryptographic hash functions:

- GOST
- MD4
- MD5
- RIPEMD-160
- SHA-1
- SHA-224
- SSH-224
- SHA-256
- SHA-384
- SHA-512
- Streebog-256
- Streebog-512
- Whirlpool

## Installation

To install Checksum.workflow, simply place this project in `~/Library/Services/` or `/Library/Services/` (which you might need to create first).

## Permissions

Upon the first use, you will likely get a prompt that says that Finder needs to control System Events. System Events is a pseudo-application that Checksum.workflow leverages to request additional information (e.g. which cryptographic hash function that you want to use). Without this permission, this workflow cannot function. If you later wish to remove this permission for some reason, then you can do so by opening System Preferences, navigating to Security & Privacy → Privacy → Automation, and unchecking “System Events.app“ within the Finder group.
