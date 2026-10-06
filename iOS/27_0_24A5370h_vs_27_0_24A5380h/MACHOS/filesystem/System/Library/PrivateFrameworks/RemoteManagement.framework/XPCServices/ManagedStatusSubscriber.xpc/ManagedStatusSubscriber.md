## ManagedStatusSubscriber

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/XPCServices/ManagedStatusSubscriber.xpc/ManagedStatusSubscriber`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfbb8` | `0x10080` | **`+0x4c8`** |
| `__DATA.__bss` | `0x140` | `0x240` | **`+0x100`** |
| `__TEXT.__const` | `0x88c` | `0x968` | **`+0xdc`** |
| `__TEXT.__cstring` | `0x2a1` | `0x341` | **`+0xa0`** |
| `__DATA_CONST.__auth_ptr` | `0xf0` | `0x138` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x381` | `0x3c5` | **`+0x44`** |
| `__TEXT.__auth_stubs` | `0x970` | `0x9a0` | **`+0x30`** |
| `__DATA.__data` | `0x760` | `0x788` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x4e0` | `0x508` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x67` | `0x87` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x4c0` | `0x4d8` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x140` | `0x150` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x180` | `0x18c` | **`+0xc`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x18` | `0x20` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-624.0.3.0.0
+624.0.8.0.0

-  Functions: 335
-  Symbols:   163
-  CStrings:  168
+  Functions: 349
+  Symbols:   166
+  CStrings:  172
Symbols:
+ _NSDebugDescriptionErrorKey
+ _NSLocalizedDescriptionKey
+ _swift_cvw_enumFn_getEnumTag
CStrings:
+ "Cannot report status on “"
+ "Error.UnsupportedStatusValue"
+ "RMErrorUserInfoKeyDescriptionKey"
+ "System health is not supported on this device."
+ "” because value is not supported. "
- "Failed to get health status: no error"
```
