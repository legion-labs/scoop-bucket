# Legion Labs Scoop Bucket

Contains dependencies not found in popular bucket or modified scripts of existing manifests used by Legion Labs.

> Visual Studio Build Tools and the Windows SDK don't support local install and they will prompt for elevation anyways. Run `scoop install sudo` prior to installing them and use the global flag as well for consistency.

| App                                        | Description                       | Install Command                             |
|--------------------------------------------|-----------------------------------|---------------------------------------------|
| [winsdk](bucket/winsdk.json)               | Windows 10 SDK                    | `sudo scoop install winsdk --global`        |
| [vs_buildtools](bucket/vs_buildtools.json) | Visual Studio Build Tools         | `sudo scoop install vs_buildtools --global` |

Add bucket using:

```powershell
scoop bucket add legionlabs https://github.com/legionlabs/scoop-bucket
```

### License

Legion Labs projects are dual-licensed under Apache 2.0 and MIT terms.

* [Apache 2.0](LICENSE-APACHE)
* [MIT](LICENSE-MIT)
