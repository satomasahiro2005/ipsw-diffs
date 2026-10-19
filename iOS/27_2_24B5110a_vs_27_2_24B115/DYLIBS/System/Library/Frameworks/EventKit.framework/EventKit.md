## EventKit

> `/System/Library/Frameworks/EventKit.framework/EventKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a3e40` | `0x1a44b8` | **`+0x678`** |
| `__TEXT.__oslogstring` | `0xf234` | `0xf294` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xaef8` | `0xaf28` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x15bcc` | `0x15bfc` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x3950` | `0x397c` | **`+0x2c`** |
| `__AUTH_CONST.__const` | `0x4500` | `0x4520` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x67c8` | `0x67e8` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x187c8` | `0x187d8` | **`+0x10`** |
| `__DATA.__bss` | `0x4750` | `0x4760` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1430` | `0x1438` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1a50` | `0x1a58` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 10709
-  Symbols:   13291
-  CStrings:  2673
+  Functions: 10717
+  Symbols:   13300
+  CStrings:  2675
Symbols:
+ +[EKAttachment _expandedArchiveTemporaryDirectoryRootForURL:]
+ +[EKAttachment _volumeIdentifierForURL:]
+ -[EKAttachment _mirroredTemporaryURLForExpandedArchiveContentsOfArchiveAtURL:]
+ -[EKAttachment localURLExpandingArchiveIfNeeded]
+ _NSURLVolumeIdentifierKey
+ _UnzipArchive
+ ___61+[EKAttachment _expandedArchiveTemporaryDirectoryRootForURL:]_block_invoke
+ __expandedArchiveTemporaryDirectoryRootForURL:.cachedRootsByVolume
+ __expandedArchiveTemporaryDirectoryRootForURL:.onceToken
CStrings:
+ "Unable to determine volume identifier for %@: %@"
+ "Unable to expand attachment archive %@"
```
