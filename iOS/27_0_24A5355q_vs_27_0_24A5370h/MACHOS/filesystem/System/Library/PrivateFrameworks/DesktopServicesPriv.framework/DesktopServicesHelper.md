## DesktopServicesHelper

> `/System/Library/PrivateFrameworks/DesktopServicesPriv.framework/DesktopServicesHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f670` | `0x8157c` | **`+0x1f0c`** |
| `__TEXT.__const` | `0x2fe0` | `0x3460` | **`+0x480`** |
| `__DATA_CONST.__const` | `0x2840` | `0x2bd0` | **`+0x390`** |
| `__TEXT.__gcc_except_tab` | `0xa114` | `0xa3bc` | **`+0x2a8`** |
| `__TEXT.__oslogstring` | `0x3507` | `0x3655` | **`+0x14e`** |
| `__TEXT.__unwind_info` | `0x37d0` | `0x38c0` | **`+0xf0`** |
| `__DATA.__data` | `0x4d1` | `0x541` | **`+0x70`** |
| `__TEXT.__cstring` | `0x27f4` | `0x2787` | **`-0x6d`** |
| `__TEXT.__auth_stubs` | `0x1900` | `0x1910` | **`+0x10`** |
| `__DATA.__common` | `0x1a2` | `0x1b0` | **`+0xe`** |
| `__DATA_CONST.__auth_got` | `0xc90` | `0xc98` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0x1dcd` | `0x1dcf` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1848.0.0.0.0
+1850.0.0.0.0

-  Functions: 2140
-  Symbols:   577
-  CStrings:  1209
+  Functions: 2214
+  Symbols:   578
+  CStrings:  1211
Symbols:
+ _CFDictionaryGetCount
+ _CFURLCreateCopyAppendingPathComponent
- _getenv
CStrings:
+ "%{public}@ - Cancelling child progress registered after op was cancelled:\n\t group progress: %{public}@\n\t child progress: %{public}@"
+ "%{public}s - operationUUID: %{public}@, progress count: %lu"
+ "%{public}s -- fBufferQueue not empty"
+ "%{public}s -- fItemQueue not empty"
+ "%{public}s progress record for op UUID: %{public}@ for url: %{public}@\n\t totalItemCount: %lld, totalFSItemCount: %lld, totalByteCount: %lld"
+ "-[DSFileServiceProgressGroup configureChildProgress:]"
+ "Adding progress record for op UUID: %{public}@ for srcURL: %{public}@\n\t destURL: %{public}@\n\t progress: %{public}@"
+ "CancelOperation"
+ "Cancelling progress for path: %{public}@\n\t progress: %{public}@"
+ "Copy root record created %d buffers, %{bytes}zu each"
+ "DSFileServiceProgressGroup -cancellationHandler: clearing pending count (was: %ld), children: %lu, progress: %{public}@"
+ "SetResourcePropertiesForKeys successful after removing %{public}@"
+ "Skipping item %{public}s on secondary thread"
+ "THelperOperationStateMap adding op ID: %d for UUID: %{public}@"
+ "THelperOperationStateMap cancelling op ID: %d for UUID: %{public}@"
+ "THelperProgressMap Unpublishing progress for url: %{public}@\n\t progress: %{public}@"
+ "THelperProgressMap removing UUID: %{public}@"
+ "THelperProgressMap removing progress before it is finished or cancelled: %{public}@ (%{public}@ / %lu), progress: %{public}@"
+ "THelperProgressMap removing progress: %{public}@ (%{public}@ / %lu), progress: %{public}@"
+ "Unpublishing progress for path: %{public}@\n\t progress: %{public}@"
+ "Updating progress record for op UUID: %{public}@ for srcURL: %{public}@\n\t destURL: %{public}@\n\t old progress: %{public}@\n\t new progress: %{public}@"
+ "Updating published progress for op UUID: %{public}@ for url: %{public}@\n\t totalItemCount: %lld, totalFSItemCount: %lld, totalByteCount: %lld\n\t progress: %{public}@"
+ "configureChildProgress:"
+ "single large file copy"
+ "too many open file descriptors, waiting for one to be closed before opening next item"
+ "too many open file descriptors. waiting for at least one to be closed."
+ "using custom buffer size %lld"
+ "~TCopyQueue"
- "%{public}s - operationUUID: %{public}@"
- "%{public}s progress record for op UUID: %{public}@, op ID: %d for url: %{public}@\n\t totalItemCount: %lld, totalFSItemCount: %lld, totalByteCount: %lld"
- "-[DSFileServiceProgressGroup observeChildProgress:]"
- "/System/Library/LaunchDaemons/com.apple.DesktopServicesHelper-libgmalloc.plist"
- "Adding progress record for op UUID: %{public}@, op ID: %d for srcURL: %{public}@\n\t destURL: %{public}@\n\t progress: %{public}@"
- "Cancel"
- "Copy root record created with bufferCount=%d bufferSize=%ld"
- "DSFileServiceProgressGroup -cancellationHandler: children: %lu, progress: %{public}@"
- "DYLD_INSERT_LIBRARIES"
- "THelperOperationStateMap adding op ID: %d"
- "THelperOperationStateMap already contains op ID: %d"
- "THelperOperationStateMap not found: %d"
- "THelperOperationStateMap removing: %d"
- "THelperOperationStateMap::CancelOperation operation not found: %d"
- "THelperProgressMap removing: %{public}@ (%{public}@ / %d / %lu)"
- "THelperProgressMap::Finalize unpublish: %{public}@"
- "Unpublishing progress for url: %{public}@\n\t progress: %{public}@"
- "Updating progress record for op UUID: %{public}@, op ID: %d for srcURL: %{public}@\n\t destURL: %{public}@\n\t old progress: %{public}@\n\t new progress: %{public}@"
- "Updating published progress for op UUID: %{public}@, op ID: %d for url: %{public}@\n\t totalItemCount: %lld, totalFSItemCount: %lld, totalByteCount: %lld\n\t progress: %{public}@"
- "com.apple.DesktopServicesHelper-libgmalloc"
- "com.apple.DesktopServicesHelper-libgmalloc.plist is not present - falling back"
- "libgmalloc"
- "observeChildProgress:"
- "too many open file descriptors open, waiting for queue to drain before opening %{public}s"
- "too many open file descriptors open, waiting for queue to drain before opening %{public}s, %{public}s"
- "too many open file descriptors open, waiting for queue to drain before opening next item"
```
