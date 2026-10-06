## PosterFoundation

> `/System/Library/PrivateFrameworks/PosterFoundation.framework/PosterFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5e500` | `0x5f134` | **`+0xc34`** |
| `__TEXT.__oslogstring` | `0x4911` | `0x4c21` | **`+0x310`** |
| `__AUTH_CONST.__cfstring` | `0x44c0` | `0x45e0` | **`+0x120`** |
| `__TEXT.__cstring` | `0x49b9` | `0x4a89` | **`+0xd0`** |
| `__DATA_CONST.__objc_selrefs` | `0x2280` | `0x22b0` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0xe28` | `0xe58` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x18e0` | `0x1910` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x14c0` | `0x14e0` | **`+0x20`** |
| `__DATA.__bss` | `0xd0` | `0xe8` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x13f8` | `0x1408` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3ab8` | `0x3ac8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xd70` | `0xd78` | **`+0x8`** |

### Other Changes

```diff

-350.1.100.0.0
+355.0.5.0.0

-  Functions: 2178
-  Symbols:   3119
-  CStrings:  1018
+  Functions: 2187
+  Symbols:   3132
+  CStrings:  1037
Symbols:
+ +[PFPosterPath reapStaleProcessScopedTemporaryDirectoriesWithPolicy:]
+ GCC_except_table34
+ GCC_except_table43
+ GCC_except_table97
+ _PFPosterPathStaleTempReapBootSessionDefaultsKey
+ _PFPosterPathStaleTempReapLastCleanupDateDefaultsKey
+ __PFCurrentBootSessionUUID
+ __PFCurrentBootSessionUUID.bootSessionUUID
+ __PFCurrentBootSessionUUID.onceToken
+ __PFReapGuardLock
+ __PFReapStaleProcessScopedTemporaryDirectories
+ __PFSweepStaleProcessScopedTemporaryDirectories
+ ____PFCurrentBootSessionUUID_block_invoke
+ ____PFReapStaleProcessScopedTemporaryDirectories_block_invoke
+ _getpid
- _OUTLINED_FUNCTION_45
- _OUTLINED_FUNCTION_46
CStrings:
+ "+[NSURL pf_directoryURLWithContainerPath:basenamePrefix:error:]: failed to create container %{public}@: %{public}@"
+ "Duvet"
+ "PFPosterPath reap stale temp"
+ "PFPosterPathStaleTempReapBootSession"
+ "PFPosterPathStaleTempReapLastCleanupDate"
+ "_temporaryDirectoryURLWithBasenamePrefix: process-local fallback also failed for prefix=%{public}@: %{public}@"
+ "_temporaryDirectoryURLWithBasenamePrefix: recovered via process-local fallback container=%{public}@ prefix=%{public}@ (override %{public}@ was unreachable)"
+ "cannot ensure reachability of a nil contentsURL"
+ "never"
+ "nobootuuid"
+ "proc-"
+ "proc-%@-"
+ "proc-%@-%d"
+ "reap: attempting cleanup for boot=%{public}@ ; %.0fs since last attempt (%{public}@)"
+ "reap: failed to list %{public}@: %{public}@"
+ "reap: failed to remove stale temp %{public}@: %{public}@"
+ "reap: no boot session UUID (kern.bootsessionuuid unavailable?); skipping"
+ "reap: removed stale process-scoped temp %{public}@"
+ "reap: sweep raised %{public}@ — abandoning (attempt already recorded, won't retry this boot)"
```
