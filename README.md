# rpi bucket

Scoop manifests for [rpi](https://github.com/bigfish1913/pi-rust), a Rust-native,
library-first coding-agent runtime and terminal CLI.

```powershell
scoop bucket add bigfish1913 https://github.com/bigfish1913/scoop-bucket
scoop install rpi
rpi --version
```

The manifest carries a GitHub `checkver`/`autoupdate` block, so new releases
follow automatically.
