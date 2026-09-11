# scoop-bucket

Scoop manifests for [alpcakin](https://github.com/alpcakin)'s tools.

```
scoop bucket add alpcakin https://github.com/alpcakin/scoop-bucket
scoop install lore
```

| Manifest | What it installs                                                |
|----------|-----------------------------------------------------------------|
| `lore`   | [A command library that lives in your shell](https://github.com/alpcakin/lore) |

Manifests carry the sha256 of the archive they install, so Scoop refuses
anything that does not match what was published with the release. A manifest
whose checksum has not been filled in yet will fail to install rather than
install something unverified.

The source of each manifest lives with the tool it installs, under `packaging/`,
and is copied here when a release is published.
