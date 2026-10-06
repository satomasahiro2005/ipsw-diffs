## AMSNearFieldExtension

> `/System/Library/ExtensionKit/Extensions/AMSNearFieldExtension.appex/AMSNearFieldExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4254` | `0x538c` | **`+0x1138`** |
| `__TEXT.__eh_frame` | `0x20c` | `0x384` | **`+0x178`** |
| `__TEXT.__auth_stubs` | `0x920` | `0xa10` | **`+0xf0`** |
| `__DATA_CONST.__auth_got` | `0x490` | `0x508` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x1a0` | `0x218` | **`+0x78`** |
| `__TEXT.__const` | `0x2c2` | `0x312` | **`+0x50`** |
| `__DATA_CONST.__got` | `0xe8` | `0x118` | **`+0x30`** |
| `__TEXT.__cstring` | `0x31c` | `0x34c` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x76` | `0x96` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x10` | `0x30` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x1c1` | `0x1dd` | **`+0x1c`** |
| `__DATA.__data` | `0x148` | `0x160` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x4` | `0x14` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x8` | `0x18` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x6c` | `0x78` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x198` | `0x1a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-8.0.52.2.8
+8.1.12.2.1

-  Functions: 140
-  Symbols:   103
-  CStrings:  24
+  Functions: 170
+  Symbols:   111
+  CStrings:  25
Symbols:
+ _objc_release_x19
+ _objc_retain_x8
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get_throwing
+ _swift_getErrorValue
+ _swift_release_x23
+ _swift_retain_x21
+ _swift_task_addCancellationHandler
+ _swift_task_removeCancellationHandler
- _swift_release_x25
- _swift_retain_x20
CStrings:
+ "Failed to load NearField localizations jetpack"
```
