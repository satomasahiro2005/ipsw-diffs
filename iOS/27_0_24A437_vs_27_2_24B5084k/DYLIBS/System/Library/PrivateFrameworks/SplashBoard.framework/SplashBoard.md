## SplashBoard

> `/System/Library/PrivateFrameworks/SplashBoard.framework/SplashBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28178` | `0x28314` | **`+0x19c`** |
| `__TEXT.__objc_methlist` | `0x2678` | `0x26a8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x277d` | `0x27a9` | **`+0x2c`** |
| `__AUTH_CONST.__cfstring` | `0x2dc0` | `0x2de0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x17e8` | `0x1808` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xa34` | `0xa54` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xd80` | `0xd88` | **`+0x8`** |

### Other Changes

```diff

-320.100.0.0.0
+321.1.1.0.0

-  Functions: 1152
-  Symbols:   1997
-  CStrings:  617
+  Functions: 1157
+  Symbols:   2001
+  CStrings:  618
Symbols:
+ +[XBApplicationSnapshotManifest _imageAccessQueue]
+ -[XBApplicationSnapshotManifestImpl _access_beginImageAccessOperation]
+ -[XBApplicationSnapshotManifestImpl _access_endImageAccessOperation]
+ -[XBApplicationSnapshotManifestImpl _pendingImageAccessOperationCount]
+ GCC_except_table100
+ GCC_except_table103
+ GCC_except_table144
+ GCC_except_table162
+ GCC_except_table169
+ GCC_except_table187
+ GCC_except_table194
- GCC_except_table102
- GCC_except_table143
- GCC_except_table158
- GCC_except_table165
- GCC_except_table183
- GCC_except_table190
- GCC_except_table99
CStrings:
+ "unbalanced -_access_endImageAccessOperation"
```
