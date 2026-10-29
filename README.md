# winerplus

Public builds for the in-app updater.

Latest: see [Releases](https://github.com/Yp777777777777/winerplus/releases).

## Mirror a new build

1. Ensure CI finished on `winerplus-src` (Release APK) and `winerplus-ios-src` (IPA).
2. Add a classic PAT with `repo` scope as secret **SOURCE_TOKEN** (needed to read private releases/artifacts).
3. Actions → **Mirror public release** → Run workflow with tag `vX.Y.Z` and version `X.Y.Z`.
