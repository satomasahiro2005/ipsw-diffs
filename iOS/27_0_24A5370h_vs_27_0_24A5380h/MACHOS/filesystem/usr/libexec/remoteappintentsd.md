## remoteappintentsd

> `/usr/libexec/remoteappintentsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x742e8` | `0x73a58` | **`-0x890`** |
| `__TEXT.__eh_frame` | `0x5b48` | `0x5940` | **`-0x208`** |
| `__TEXT.__unwind_info` | `0x1ef8` | `0x1e28` | **`-0xd0`** |
| `__TEXT.__cstring` | `0x1418` | `0x1388` | **`-0x90`** |
| `__TEXT.__const` | `0x2368` | `0x2308` | **`-0x60`** |
| `__TEXT.__swift_as_cont` | `0x3ec` | `0x3a0` | **`-0x4c`** |
| `__DATA.__data` | `0x22a8` | `0x2278` | **`-0x30`** |
| `__DATA_CONST.__auth_ptr` | `0xad8` | `0xaf0` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x14d4` | `0x14ea` | **`+0x16`** |
| `__DATA_CONST.__got` | `0x7d8` | `0x7c8` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x2ad0` | `0x2ac0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x1570` | `0x1568` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x28c` | `0x288` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x2a4` | `0x2a0` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-41.0.42.6.0
+41.0.43.7.0

-  Functions: 2728
-  Symbols:   1103
-  CStrings:  562
+  Functions: 2654
+  Symbols:   1100
+  CStrings:  560
Symbols:
+ _swift_retain_x9
- _$s15Synchronization5MutexVMa
- _$ss9TaskLocalC9withValue_9operation9isolation4file4lineqd__x_qd__yYaKXEScA_pSgYiSSSutYaKlF
- _$ss9TaskLocalC9withValue_9operation9isolation4file4lineqd__x_qd__yYaKXEScA_pSgYiSSSutYaKlFTu
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
- "RemoteAppIntentsDaemon/AppNotificationEventRegistry+Observer.swift"
- "RemoteAppIntentsDaemon/Instrumentation+Extensions.swift"
```
