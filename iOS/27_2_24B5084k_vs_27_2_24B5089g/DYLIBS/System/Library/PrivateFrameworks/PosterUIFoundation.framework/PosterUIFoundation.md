## PosterUIFoundation

> `/System/Library/PrivateFrameworks/PosterUIFoundation.framework/PosterUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x950b0` | `0x968c4` | **`+0x1814`** |
| `__TEXT.__oslogstring` | `0x3a51` | `0x40c1` | **`+0x670`** |
| `__TEXT.__cstring` | `0x67d3` | `0x6913` | **`+0x140`** |
| `__AUTH_CONST.__cfstring` | `0x8060` | `0x8180` | **`+0x120`** |
| `__TEXT.__gcc_except_tab` | `0x17bc` | `0x1898` | **`+0xdc`** |
| `__DATA_CONST.__const` | `0x2720` | `0x2778` | **`+0x58`** |
| `__AUTH_CONST.__auth_got` | `0x10c0` | `0x1110` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x1f038` | `0x1f078` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x5938` | `0x5978` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x29e8` | `0x2a20` | **`+0x38`** |
| `__TEXT.__const` | `0xdc4` | `0xde4` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xabdc` | `0xabfc` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xfb8` | `0xfc8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xbe4` | `0xbec` | **`+0x8`** |

### Other Changes

```diff

-355.2.4.0.0
+355.2.6.200.0

-  Functions: 4161
-  Symbols:   7431
-  CStrings:  1510
+  Functions: 4171
+  Symbols:   7455
+  CStrings:  1543
Symbols:
+ -[PUIPosterSnapshotBundle _cacheImage:forLevelSet:decodedFromIdentifier:]
+ -[PUIPosterSnapshotBundle _pui_afscObserveCompressionIfNeeded]
+ -[PUIPosterSnapshotBundle dealloc]
+ GCC_except_table7
+ _NSURLFileResourceIdentifierKey
+ _OBJC_CLASS_$_NSNotificationCenter
+ _OBJC_IVAR_$_PUIPosterSnapshotBundle._afscCompressionObserver
+ _OBJC_IVAR_$_PUIPosterSnapshotBundle._decodedImages
+ _PUIAFSCCompressionBundleURLKey
+ _PUIAFSCCompressionFileNamesKey
+ _PUIAFSCDidCompressBundleNotificationForBundle
+ ___62-[PUIPosterSnapshotBundle _pui_afscObserveCompressionIfNeeded]_block_invoke
+ ___block_descriptor_40_e8_32s_e24_v16?0"NSNotification"8ls32l8
+ __pui_afscCloneProtectionVerdict
+ __pui_afscPathIsAlreadyCompressed
+ _clonefile
+ _close
+ _fcntl
+ _listxattr
+ _malloc_type_malloc
+ _open
+ _pread
+ _renamex_np
+ _stat
+ _unlink
- GCC_except_table40
CStrings:
+ "(could not compare)"
+ "AFSC CompressFile refused %{public}@; leaving it uncompressed"
+ "AFSC clone of %{public}@ did not keep the source's protection class; discarding it"
+ "AFSC clone of %{public}@ lost xattr %{public}@; discarding it"
+ "AFSC compressed %lu file(s) under %{public}@ in %.1fms"
+ "AFSC compressed %lu of %lu file(s) under %{public}@ in %.1fms: %{public}@"
+ "AFSC compressed %{public}@ (%lld -> %lld bytes, %.0f%% smaller) in %.1fms (inode %llu -> %llu)"
+ "AFSC compressing %lu file(s) under %{public}@"
+ "AFSC could not clone %{public}@ (%{darwin.errno}d); leaving it uncompressed"
+ "AFSC could not compare the protection class of %{public}@ (%{darwin.errno}d); discarding the compressed copy"
+ "AFSC could not discard the clone of %{public}@ (%{darwin.errno}d); it stays on disk until the next sweep"
+ "AFSC could not identify %{public}@, so no holder will drop its cached decodes: %{public}@"
+ "AFSC could not stat %{public}@ (%{darwin.errno}d); skipping it"
+ "AFSC could not swap in %{public}@ (%{darwin.errno}d); discarding the compressed copy"
+ "AFSC failed on %lu of %lu file(s); see the per-file errors above"
+ "AFSC left %{public}@ (%lld bytes) uncompressed after %.1fms"
+ "AFSC produced no usable compressed copy of %{public}@: %{public}@ (%{darwin.errno}d)"
+ "AFSC skipped %lu already-compressed file(s) under %{public}@; nothing to do"
+ "AFSC skipped %{public}@ (%lld bytes), already compressed"
+ "AFSC source %{public}@ was rewritten during compression (inode %llu -> %llu); discarding the compressed copy"
+ "AFSC source %{public}@ went away during compression (%{darwin.errno}d); discarding the compressed copy"
+ "AFSC swapped in %{public}@ but could not read its new inode"
+ "AFSC swapped in %{public}@ but could not remove the old copy (%{darwin.errno}d)"
+ "AFSC swept a stale clone at %{public}@"
+ "PUIAFSCCompressionBundleURL"
+ "PUIAFSCCompressionFileNames"
+ "PUIAFSCDidCompressBundle-%@"
+ "afsctmp"
+ "already compressed"
+ "compressed %lu, declined %lu, already %lu, failed %lu"
+ "stat failed"
+ "the clone is not the size the source was"
+ "the clone reports the right size but its last byte will not decode"
+ "the clone vanished"
+ "the clone would not open"
+ "v16@?0@\"NSNotification\"8"
- "AFSC CompressFile rejected every path"
- "AFSC compressed %lu of %lu file(s) under %{public}@ (remainder left uncompressed): %{public}@"
- "compressed %lu of %lu"
```
