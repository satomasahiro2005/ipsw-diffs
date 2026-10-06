## HomeNotification

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeNotification.appex/HomeNotification`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x253b8` | `0x264c4` | **`+0x110c`** |
| `__TEXT.__cstring` | `0x16ae` | `0x17de` | **`+0x130`** |
| `__TEXT.__eh_frame` | `0x84c` | `0x92c` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x1048` | `0x1098` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x7f4` | `0x844` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x850` | `0x898` | **`+0x48`** |
| `__TEXT.__objc_methtype` | `0xb32` | `0xb62` | **`+0x30`** |
| `__DATA.__data` | `0x910` | `0x930` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1710` | `0x1730` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2da0` | `0x2dc0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xb98` | `0xba8` | **`+0x10`** |
| `__TEXT.__const` | `0x8b8` | `0x8c8` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x194` | `0x1a4` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2b2` | `0x2c2` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x218` | `0x224` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x30` | `0x3c` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0xfb0` | `0xfb8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x490` | `0x498` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x1c` | `0x24` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x18` | `0x1c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1238.0.0.0.0
+1241.1.7.1.2

-  Functions: 648
-  Symbols:   333
-  CStrings:  954
+  Functions: 664
+  Symbols:   334
+  CStrings:  960
Symbols:
+ _OBJC_CLASS_$_HMCameraSource
CStrings:
+ "Failed to fetch still snapshot (error: %{public}@)"
+ "Failed to find camera profile or snapshot control for still snapshot"
+ "Feedback gate – isReduceNotificationsAvailable=%{public}@"
+ "Fetched still snapshot"
+ "fetchStillSnapshotIfNeeded(userInfo:cameraProfileID:)"
+ "serviceFor:"
```
