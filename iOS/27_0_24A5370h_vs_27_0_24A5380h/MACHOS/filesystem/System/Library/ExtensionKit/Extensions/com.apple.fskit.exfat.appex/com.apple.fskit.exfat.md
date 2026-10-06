## com.apple.fskit.exfat

> `/System/Library/ExtensionKit/Extensions/com.apple.fskit.exfat.appex/com.apple.fskit.exfat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12454` | `0x12434` | **`-0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_100001478 : 140 -> 148
~ _fsck_exfat_name_hash : 296 -> 272
~ _convertfmt : 648 -> 644
~ _check_reformat : 1272 -> 1276
~ _exfat_format_defaults : 492 -> 496
~ _localizeFSCKMessage : 376 -> 360
~ _localizeNewFSMessage : 408 -> 404
```
