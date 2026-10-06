## FileIndexerDaemon

> `/System/Library/PrivateFrameworks/FileIndexerDaemon.framework/FileIndexerDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6bfc8` | `0x6df80` | **`+0x1fb8`** |
| `__TEXT.__oslogstring` | `0x26aa` | `0x281a` | **`+0x170`** |
| `__TEXT.__eh_frame` | `0x1e70` | `0x1fa0` | **`+0x130`** |
| `__AUTH_CONST.__const` | `0x2a00` | `0x2ac8` | **`+0xc8`** |
| `__TEXT.__const` | `0x34f4` | `0x3574` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x1248` | `0x12a8` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x8ac` | `0x904` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x11b4` | `0x11d6` | **`+0x22`** |
| `__TEXT.__cstring` | `0x146b` | `0x148b` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x46c` | `0x488` | **`+0x1c`** |
| `__DATA_DIRTY.__data` | `0x1f48` | `0x1f30` | **`-0x18`** |
| `__TEXT.__constg_swiftt` | `0x12e8` | `0x1300` | **`+0x18`** |
| `__DATA.__data` | `0x760` | `0x770` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0xd8e` | `0xd7e` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0x68` | `0x74` | **`+0xc`** |
| `__AUTH.__data` | `0x98` | `0xa0` | **`+0x8`** |
| `__AUTH_CONST.__auth_got` | `0xf70` | `0xf78` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0x19f8` | `0x1a00` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x548` | `0x550` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x4f8` | `0x500` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x88` | `0x90` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x60` | `0x68` | **`+0x8`** |

### Other Changes

```diff

-4838.0.93.0.0
+4838.0.125.0.0

-  Functions: 1627
-  Symbols:   823
-  CStrings:  299
+  Functions: 1652
+  Symbols:   826
+  CStrings:  307
Symbols:
+ ___swift_closure_destructor.101Tm
+ ___swift_closure_destructor.132Tm
+ ___swift_closure_destructor.136Tm
+ ___swift_closure_destructor.202Tm
+ ___swift_closure_destructor.52Tm
+ ___swift_closure_destructor.82Tm
+ ___swift_closure_destructor.85Tm
+ _dispatch_async_and_wait
+ _symbolic SS_ypt
+ _symbolic So7NSArrayC
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
- ___swift_closure_destructor.118Tm
- ___swift_closure_destructor.295Tm
- ___swift_closure_destructor.329Tm
- ___swift_closure_destructor.45Tm
- ___swift_closure_destructor.48Tm
- ___swift_closure_destructor.93Tm
- ___swift_closure_destructor.97Tm
- _dispatch_sync
CStrings:
+ "%ld scans added"
+ "Registering local storage indexing DAS task"
+ "Setting up FIRoot"
+ "Setting up roots for FileIndexer"
+ "[DiskStateStore] loading indexing state %s"
+ "[DiskStateStore] successfully loaded state from disk with state: %s"
+ "out-of-band index: GSLibraryResolveDocumentId2 for did=%u failed with errno=%d, skipping"
+ "out-of-band index: identifiers %{public}s"
+ "outOfBandIndex(keys:)"
- "Attempting to load indexing state from disk"
```
