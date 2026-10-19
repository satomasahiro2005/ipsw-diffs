## CalendarFoundation

> `/System/Library/PrivateFrameworks/CalendarFoundation.framework/CalendarFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x64ff0` | `0x665a4` | **`+0x15b4`** |
| `__TEXT.__oslogstring` | `0x39a5` | `0x3d55` | **`+0x3b0`** |
| `__TEXT.__gcc_except_tab` | `0xaf8` | `0xbcc` | **`+0xd4`** |
| `__AUTH_CONST.__cfstring` | `0x9580` | `0x95e0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x6602` | `0x6662` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0xcb8` | `0xd08` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1cc0` | `0x1cf8` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x1790` | `0x17b8` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x41d8` | `0x4200` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x5db4` | `0x5dcc` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x910` | `0x918` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 2753
-  Symbols:   4480
-  CStrings:  1567
+  Functions: 2774
+  Symbols:   4502
+  CStrings:  1585
Symbols:
+ +[CalAttachmentUtils URL:isContainedInDirectory:]
+ +[CalAttachmentUtils isSymbolicLinkAtURL:]
+ GCC_except_table10
+ _BOMCopierCancelCopy
+ _BOMCopierSetCopyFileFinishedHandler
+ _BOMCopierSetCopyFileStartedHandler
+ _BOMCopierSetCopyFileUpdateHandler
+ _BOMCopierUserData
+ _UnzipArchiveWithLimits
+ __CalUnzipCopyFileFinished
+ __CalUnzipCopyFileStarted
+ __CalUnzipCopyFileUpdate
+ __CalUnzipEntryDestinationPath
+ __CalUnzipParentIsContained
+ __CalUnzipTrackTopLevelPath
+ ____CalUnzipRemoveEscapingSymlinks_block_invoke
+ ___block_descriptor_40_e8_32r_e27_B24?0"NSURL"8"NSError"16lr32l8
+ _lstat
+ _realpath$DARWIN_EXTSN
+ _strcmp
+ _strncmp
+ _unlink
CStrings:
+ ".."
+ "Archive contains a symlink pointing outside destination; removing it. entry = %@"
+ "Archive entry exceeds total size limit (%llu bytes); canceling extraction."
+ "Archive entry resolves outside destination; canceling extraction. entry = %s"
+ "Archive entry's parent directory escapes destination (likely via an earlier symlink entry); canceling extraction. entry = %s"
+ "Archive exceeds item count limit (%lu); canceling extraction."
+ "Archive exceeds total size limit (%llu bytes) while writing an entry; canceling extraction."
+ "Archive exceeds total size limit (%llu bytes); canceling extraction."
+ "B24@?0@\"NSURL\"8@\"NSError\"16"
+ "Could not lstat %@: %d"
+ "Could not resolve %@ or %@: %d"
+ "Could not resolve destination %@: %d; refusing to extract."
+ "Failed to enumerate extracted archive contents at %@: %@; treating as unsafe."
+ "Failed to remove debris left by a failed extraction at %@: %@"
+ "Failed to remove escaping symlink: %d"
+ "Refusing to remove %@: its parent directory is not contained in destination."
+ "enforceDestinationEncapsulation"
+ "enforceDestinationLocation"
```
