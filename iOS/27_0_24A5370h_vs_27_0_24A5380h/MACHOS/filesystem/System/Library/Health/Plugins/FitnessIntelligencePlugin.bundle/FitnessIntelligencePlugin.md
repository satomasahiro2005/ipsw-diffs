## FitnessIntelligencePlugin

> `/System/Library/Health/Plugins/FitnessIntelligencePlugin.bundle/FitnessIntelligencePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f3a4` | `0x80554` | **`+0x11b0`** |
| `__TEXT.__eh_frame` | `0x1bd8` | `0x1d18` | **`+0x140`** |
| `__TEXT.__auth_stubs` | `0x1e40` | `0x1f30` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0x138f` | `0x142f` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0xf28` | `0xfa0` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x12d0` | `0x1328` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x42c8` | `0x4318` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x1168` | `0x119c` | **`+0x34`** |
| `__TEXT.__const` | `0x15b8` | `0x15e8` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x10ec` | `0x1110` | **`+0x24`** |
| `__TEXT.__swift5_typeref` | `0x12ea` | `0x130e` | **`+0x24`** |
| `__TEXT.__objc_stubs` | `0x760` | `0x780` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x538` | `0x550` | **`+0x18`** |
| `__DATA.__data` | `0x16f8` | `0x1708` | **`+0x10`** |
| `__DATA.__objc_const` | `0x15e8` | `0x15f8` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x4c0` | `0x4d0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `—` | `0xc` | **`+0xc`** |
| `__DATA.__objc_data` | `0x12a0` | `0x12a8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xbb4` | `0xbbc` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-2027.0.66.0.0
+2027.0.71.0.0

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 1796
-  Symbols:   232
-  CStrings:  515
+  Functions: 1813
+  Symbols:   237
+  CStrings:  519
Symbols:
+ _notify_post
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
CStrings:
+ "[%s] A workout completed, release FitnessIntelligence os transaction"
+ "[%s] Failed to invalidate OSTransaction: %@. Sending Darwin Notification"
+ "publicState"
+ "touchWithCompletion:"
```
