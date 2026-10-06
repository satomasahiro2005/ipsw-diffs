## FileIndexerDaemon

> `/System/Library/PrivateFrameworks/FileIndexerDaemon.framework/FileIndexerDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68164` | `0x6bfc8` | **`+0x3e64`** |
| `__TEXT.__oslogstring` | `0x23fa` | `0x26aa` | **`+0x2b0`** |
| `__DATA.__bss` | `0x2d80` | `0x2f80` | **`+0x200`** |
| `__AUTH_CONST.__const` | `0x2878` | `0x2a00` | **`+0x188`** |
| `__TEXT.__const` | `0x3374` | `0x34f4` | **`+0x180`** |
| `__TEXT.__swift5_reflstr` | `0xcc8` | `0xd8e` | **`+0xc6`** |
| `__TEXT.__swift5_fieldmd` | `0xf14` | `0xfb8` | **`+0xa4`** |
| `__DATA_DIRTY.__data` | `0x1fd8` | `0x1f48` | **`-0x90`** |
| `__TEXT.__cstring` | `0x13fb` | `0x146b` | **`+0x70`** |
| `__DATA.__data` | `0x6f8` | `0x760` | **`+0x68`** |
| `__AUTH_CONST.__auth_got` | `0xf20` | `0xf70` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x11f8` | `0x1248` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x12a0` | `0x12e8` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x1e48` | `0x1e70` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x884` | `0x8ac` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x19d8` | `0x19f8` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x64` | `0x78` | **`+0x14`** |
| `__TEXT.__swift5_typeref` | `0x11a0` | `0x11b4` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x274` | `0x284` | **`+0x10`** |
| `__AUTH.__data` | `0xa0` | `0x98` | **`-0x8`** |
| `__DATA.__common` | `0x20` | `0x28` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x540` | `0x548` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x4f0` | `0x4f8` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xf8` | `0x100` | **`+0x8`** |

### Other Changes

```diff

-4838.0.70.0.0
+4838.0.93.0.0

+  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

+  - /System/Library/PrivateFrameworks/GenerationalStorage.framework/GenerationalStorage

-  Functions: 1581
-  Symbols:   814
-  CStrings:  286
+  Functions: 1627
+  Symbols:   823
+  CStrings:  299
Symbols:
+ _GSLibraryResolveDocumentId2
+ ___swift_memcpy18_8
+ ___swift_memcpy28_8
+ ___swift_memcpy9_8
+ _associated conformance 17FileIndexerDaemon17SearchableItemKeyOSHAASQ
+ _fpfs_should_be_tracked
+ _fpfs_track_document
+ _fpfs_untrack_document
+ _symbolic Say_____G 17FileIndexerDaemon17SearchableItemKeyO
+ _symbolic Say_____GSay_____GSay_____G_____Ieggggr_ 17FileIndexerDaemon0A8MetadataV AA17SearchableItemKeyO 10Foundation3URLV AA10IndexBatchV
+ _symbolic _____ 17FileIndexerDaemon17SearchableItemKeyO
+ _symbolic _____ 17FileIndexerDaemon20IndexByDocumentIDKey33_B422E588E7EC79FE565E0A561647CF95LLV
+ _symbolic ___________Sg4scant 17FileIndexerDaemon17SearchableItemKeyO 10Foundation3URLV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 17FileIndexerDaemon17SearchableItemKeyO
+ _type_layout_string 17FileIndexerDaemon0A7HandlerV
- ___swift_memcpy17_8
- ___swift_memcpy20_8
- _symbolic Say_____G s6UInt64V
- _symbolic Say_____GSay_____GSay_____G_____Ieggggr_ 17FileIndexerDaemon0A8MetadataV s6UInt64V 10Foundation3URLV AA10IndexBatchV
- _symbolic ___________Sg4scant s6UInt64V 10Foundation3URLV
- _symbolic _____y_____G s23_ContiguousArrayStorageC s6UInt64V
CStrings:
+ "%{public}s treated as deleted: %{public}s"
+ "FileIndexer"
+ "GSLibraryResolveDocumentId2 failed for did=%u, dev=%d: errno=%d (%s), falling back to event.fileID=%llu"
+ "GSLibraryResolveDocumentId2 failed for did=%u: errno=%d"
+ "IndexByDocumentID"
+ "[DiskStateStore] indexing mode flip detected: cookie indexByDocumentID=%{bool}d, active=%{bool}d -- forcing re-index"
+ "clearUFTracked failed for fid=%llu, dev=%d: %{public}@"
+ "fetchDocumentID open() failed for %{public}s: errno=%d"
+ "fpfs_should_be_tracked failed for fd=%d: errno=%d"
+ "fpfs_track_document failed for fd=%d: errno=%d"
+ "fpfs_untrack_document failed for did=%llu, dev=%d: errno=%d"
+ "indexByDocumentID"
+ "list(fd:page:maxCount:appContainerBundleID:indexByDocumentID:)"
+ "no docID; fileID="
+ "resourceValues(.isPackageKey) failed for %{public}s: %{public}@"
- "%llu does not exist"
- "list(fd:page:maxCount:appContainerBundleID:)"
```
