# Pica Bridge Windows updates

Signed Windows x64 installers and update metadata for Pica Bridge. Application source is maintained in a private repository.

The app automatically checks `latest.json`, verifies the installer signature and version, then installs and restarts while preserving the existing Windows user's app data.

Published versions are immutable. Download a numbered installer from `releases/`; do not delete the existing app data when upgrading. Installers are signed for the app updater; they do not currently have a Windows Authenticode certificate.
