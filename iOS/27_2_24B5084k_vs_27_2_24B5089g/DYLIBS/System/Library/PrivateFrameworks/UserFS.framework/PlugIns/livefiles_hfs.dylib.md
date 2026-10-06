## livefiles_hfs.dylib

> `/System/Library/PrivateFrameworks/UserFS.framework/PlugIns/livefiles_hfs.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d4f0` | `0x3d750` | **`+0x260`** |
| `__TEXT.__oslogstring` | `0x5ed7` | `0x5f0f` | **`+0x38`** |

### Other Changes

```diff

-753.40.2.0.0
+753.40.3.0.0

-  CStrings:  751
+  CStrings:  752
Functions:
~ _hfs_vnop_setxattr : 3008 -> 3616
CStrings:
+ "hfs_setxattr: orphan overflow attr record vol=%s %d,%s\n"
```
