## PosterUIFoundation

> `/System/Library/PrivateFrameworks/PosterUIFoundation.framework/PosterUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x93db0` | `0x94d08` | **`+0xf58`** |
| `__TEXT.__oslogstring` | `0x38a1` | `0x3a21` | **`+0x180`** |
| `__TEXT.__gcc_except_tab` | `0x1674` | `0x17ac` | **`+0x138`** |
| `__TEXT.__cstring` | `0x6663` | `0x6783` | **`+0x120`** |
| `__AUTH_CONST.__cfstring` | `0x7f20` | `0x7fc0` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x69c` | `0x708` | **`+0x6c`** |
| `__DATA_CONST.__objc_selrefs` | `0x58c8` | `0x5910` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x10c0` | `0x1100` | **`+0x40`** |
| `__DATA.__bss` | `0x8c0` | `0x900` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1090` | `0x10c0` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x1ef80` | `0x1efb0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x26f8` | `0x2720` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xf90` | `0xfb8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xab64` | `0xab7c` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x7f2` | `0x80a` | **`+0x18`** |
| `__TEXT.__const` | `0xdb4` | `0xdc4` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x29d0` | `0x29e0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xbdc` | `0xbe0` | **`+0x4`** |

### Other Changes

```diff

-350.1.100.0.0
+355.0.5.0.0

-  Functions: 4136
-  Symbols:   7395
-  CStrings:  1489
+  Functions: 4155
+  Symbols:   7425
+  CStrings:  1504
Symbols:
+ -[PUIPosterSnapshotHostConfigurationDescriptor abortsIfBacklightNotFull]
+ -[PUIPosterSnapshotHostConfigurationDescriptor copyWithAbortsIfBacklightNotFull:]
+ -[PUIPosterSnapshotHostConfigurationDescriptor initWithHostWorkQueue:waitUntilReady:inProcessSnapshot:abortsIfBacklightNotFull:]
+ _NSURLContentTypeKey
+ _NSURLIsDirectoryKey
+ _NSURLIsRegularFileKey
+ _OBJC_IVAR_$_PUIPosterSnapshotHostConfigurationDescriptor._abortsIfBacklightNotFull
+ _PUIAFSCCompressFilesAtPaths
+ _PUIAFSCEnqueueCompressionForURL
+ _UTTypeImage
+ ___PUIAFSCEnqueueCompressionForURL_block_invoke
+ ___PUIAFSCEnqueueCompressionForURL_block_invoke_2
+ ____pui_afscQueue_block_invoke
+ ____pui_afscWorkBegan_block_invoke
+ ___block_descriptor_40_e8_32s_e27_B24?0"NSURL"8"NSError"16ls32l8
+ ___getkAFSCIgnoreXattrErrorsSymbolLoc_block_invoke
+ __pui_afscLock
+ __pui_afscLock_assertion
+ __pui_afscLock_generation
+ __pui_afscLock_pendingCount
+ __pui_afscQueue.onceToken
+ __pui_afscQueue.queue
+ _dispatch_queue_attr_make_with_qos_class
+ _dispatch_queue_create
+ _get_witness_table 7SwiftUI4ViewRzAaBRd__r__lqd0__AaBHD3_AaBPAAE5sheet11isPresented9onDismiss7contentQrAA7BindingVySbG_yycSgqd__yctAaBRd__lFQOyx_qd__Qo_HO
+ _get_witness_table 7SwiftUI4ViewRzAaBRd__r__lqd0__AaBHD3_AaBPAAE5sheet11isPresented9onDismiss7contentQrAA7BindingVySbG_yycSgqd__yctAaBRd__lFQOyx_qd__Qo_HOTm
+ _getkAFSCIgnoreXattrErrorsSymbolLoc.ptr
+ _objc_begin_catch
+ _objc_end_catch
+ _objc_exception_rethrow
+ _symbolic _____yx_qd__Qo_ 7SwiftUI4ViewPAAE5sheet11isPresented9onDismiss7contentQrAA7BindingVySbG_yycSgqd__yctAaBRd__lFQO
- -[PUIPosterSnapshotHostConfigurationDescriptor initWithHostWorkQueue:waitUntilReady:inProcessSnapshot:]
CStrings:
+ "%lu file(s)"
+ "%{public}@"
+ "(%p) Aborting capture; scene backlight not full (%ld)."
+ "AFSC CompressFile rejected every path"
+ "AFSC compressed %lu of %lu file(s) under %{public}@ (remainder left uncompressed): %{public}@"
+ "AFSC compressing poster snapshots"
+ "AFSC could not determine whether %{public}@ is a directory: %{public}@"
+ "AFSC enumeration error under %{public}@ at %{public}@: %{public}@"
+ "AFSC prewarm assertion invalidated or failed to acquire; remaining compression is unprotected: %{public}@"
+ "AFSC work ended without a matching begin"
+ "B24@?0@\"NSURL\"8@\"NSError\"16"
+ "No path was on an AFSC-capable volume"
+ "PUIAFSCCompressFile"
+ "PUIAFSCCompressFilesAtPaths"
+ "Unable to interpret path"
+ "_abortsIfBacklightNotFull"
+ "abortsIfBacklightNotFull"
+ "com.apple.posteruifoundation.afsc-compression"
+ "compressed %lu of %lu"
+ "compressed=%d"
+ "kAFSCIgnoreXattrErrors"
+ "scene backlight not full; aborting to avoid a black snapshot"
- "AFSC CompressFile rejected the path"
- "AFSC compression failed for %{public}@ (uncompressed file left in place): %{public}@"
- "CompressFile rejected"
- "PUIAFSCCompressFileAtPath"
- "Volume does not support AFSC"
- "success"
- "unsupported"
```
