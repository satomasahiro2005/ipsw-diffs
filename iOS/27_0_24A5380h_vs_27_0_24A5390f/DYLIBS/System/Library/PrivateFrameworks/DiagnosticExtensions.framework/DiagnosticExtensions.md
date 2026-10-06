## DiagnosticExtensions

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/DiagnosticExtensions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17acc` | `0x17dfc` | **`+0x330`** |
| `__TEXT.__oslogstring` | `0x32b9` | `0x3348` | **`+0x8f`** |
| `__AUTH_CONST.__auth_got` | `0x590` | `0x5a0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1256` | `0x1248` | **`-0xe`** |
| `__TEXT.__gcc_except_tab` | `0x50c` | `0x518` | **`+0xc`** |
| `__DATA_DIRTY.__bss` | `0xe8` | `0xe0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x6b0` | `0x6b8` | **`+0x8`** |

### Other Changes

```diff

-147.0.0.0.0
+148.0.0.0.0

-  Functions: 591
-  Symbols:   999
-  CStrings:  436
+  Functions: 594
+  Symbols:   1000
+  CStrings:  439
Symbols:
+ _NSURLIsSymbolicLinkKey
+ _archive_entry_set_symlink
+ _lstat
+ _readlink
- __dispatch_queue_attr_concurrent
- _extendedQueue
- _stat
Functions:
~ -[DEArchive addFile:withPathName:progressHandler:] : 1428 -> 1892
+ _OUTLINED_FUNCTION_0
~ +[DEArchiver archiveDirectoryAt:deleteOriginal:progressHandler:] : 1612 -> 1724
- _OUTLINED_FUNCTION_1
~ ___36+[DEExtensionManager sharedInstance]_block_invoke : 164 -> 60
~ -[DEExtensionManager init] : 56 -> 120
~ +[DEUtils pathComponentsInURL:removingBaseURLComponents:keepingFirstComponent:] : 256 -> 308
~ -[DEArchive addFile:withPathName:progressHandler:].cold.1 : 100 -> 92
~ -[DEArchive addFile:withPathName:progressHandler:].cold.2 : 112 -> 64
~ -[DEArchive addFile:withPathName:progressHandler:].cold.3 : 64 -> 92
+ -[DEArchive addFile:withPathName:progressHandler:].cold.4
+ -[DEArchive addFile:withPathName:progressHandler:].cold.6
+ -[DEArchive archiverForUrl:].cold.2
CStrings:
+ "Error [%@] getting NSURLIsSymbolicLinkKey for url [%@]"
+ "Error reading file"
+ "lstat failed for [%s]: %{errno}d"
+ "readlink failed for [%s]: %{errno}d"
- "extendedQueue"
```
