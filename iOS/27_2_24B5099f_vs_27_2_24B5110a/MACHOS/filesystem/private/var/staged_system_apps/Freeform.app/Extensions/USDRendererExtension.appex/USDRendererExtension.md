## USDRendererExtension

> `/private/var/staged_system_apps/Freeform.app/Extensions/USDRendererExtension.appex/USDRendererExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7abd0` | `0x7c3f8` | **`+0x1828`** |
| `__TEXT.__eh_frame` | `0x5148` | `0x5678` | **`+0x530`** |
| `__DATA_CONST.__const` | `0x4918` | `0x4728` | **`-0x1f0`** |
| `__TEXT.__const` | `0x6da8` | `0x6ee8` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0x9d85` | `0x9e85` | **`+0x100`** |
| `__TEXT.__swift5_capture` | `0x8a0` | `0x7b8` | **`-0xe8`** |
| `__TEXT.__unwind_info` | `0x2948` | `0x2a30` | **`+0xe8`** |
| `__TEXT.__swift5_typeref` | `0x1aba` | `0x1b66` | **`+0xac`** |
| `__DATA.__objc_const` | `0x5ec0` | `0x5f28` | **`+0x68`** |
| `__TEXT.__swift_as_cont` | `0x3fc` | `0x450` | **`+0x54`** |
| `__TEXT.__objc_methtype` | `0x378a` | `0x37d7` | **`+0x4d`** |
| `__TEXT.__objc_stubs` | `0x21a0` | `0x21e0` | **`+0x40`** |
| `__TEXT.__swift_as_entry` | `0x18c` | `0x1c4` | **`+0x38`** |
| `__TEXT.__swift_as_ret` | `0x1a0` | `0x1d8` | **`+0x38`** |
| `__DATA.__data` | `0x33a0` | `0x3370` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0x20c8` | `0x20d8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2da0` | `0x2db0` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0xb45` | `0xb35` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x16e0` | `0x16e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-656.40.8.0.0
+656.40.9.0.2

-  Functions: 3007
-  Symbols:   651
-  CStrings:  2093
+  Functions: 3041
+  Symbols:   652
+  CStrings:  2096
Symbols:
+ _OBJC_CLASS_$_NSLock
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
- _RECameraViewDescriptorsComponentSnapshotNextFrameWithSettings
- _RERenderGraphCreateRenderGraphDataStruct
CStrings:
+ "isFinished"
+ "lock"
+ "renderSnapshotFrame(into:)"
+ "resultBeforeAttaching"
+ "unlock"
- "SnapshotViewDescriptorSettings"
- "snapshotRequests"
```
