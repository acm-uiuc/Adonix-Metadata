# Adonix-Metadata
Config files for Adonix

## Versioning 
Used to notify users that there has been an app update. 
- Versions must be in the format `year.version.patch`, ex: 2024.1.1
- iOS and Android devices must be on the same `year.version`, use `patch` for hotfixes which can differ
- Frontends should verify that `their version >= API version`
  - If not, then display popup to urge user to update their app
- Everytime iOS or Android changes their version, i.e. deploys to prod in Play Store or App Store, they must create a PR on this repo to update the API version to match

API lead, iOS lead, Android leads must communicate through this process :) 
