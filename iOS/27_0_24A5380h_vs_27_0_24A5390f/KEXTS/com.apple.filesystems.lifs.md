## com.apple.filesystems.lifs

> `com.apple.filesystems.lifs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x20244` | `0x20390` | **`+0x14c`** |
| `__TEXT.__os_log` | `0x1eba` | `0x1f16` | **`+0x5c`** |
| `__TEXT.__cstring` | `0x29e6` | `0x29fa` | **`+0x14`** |

### Other Changes

```diff

-974.0.7.0.0
+974.0.11.0.0

-  CStrings:  517
+  CStrings:  519
Functions:
~ _lifs_vnop_getattrlistbulk : 1300 -> 1380
~ _lifs_getfsattr_call : 360 -> 384
~ _lifs_mntfromname : 484 -> 496
~ sub_fffffff00aac910c -> sub_fffffff00aaef910 : 792 -> 848
~ sub_fffffff00aac9524 -> _lifs_readdir_cached : 752 -> 912
CStrings:
+ "%s: Got LIFS_DIRCACHE_LIMIT_REACHED with offset > 0, but no matching cookie entry was found"
+ "lifs_readdir_cached"
```
