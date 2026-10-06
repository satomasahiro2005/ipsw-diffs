## com.apple.fskit.hfs

> `/System/Library/ExtensionKit/Extensions/com.apple.fskit.hfs.appex/com.apple.fskit.hfs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16e8` | `0x16ec` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-747.0.0.0.0
+748.0.0.0.0
Functions:
~ _hfs_GetVolumeUUIDRaw : 396 -> 392
~ _hfs_GetNameFromHFSPlusVolumeStartingAt : 1368 -> 1364
~ sub_100002074 -> sub_10000206c : 284 -> 296
```
