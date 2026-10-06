## AXHapticMusicServer

> `/System/Library/AccessibilityBundles/AXHapticMusicServer.axuiservice/AXHapticMusicServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b644` | `0x2b6c8` | **`+0x84`** |
| `__TEXT.__oslogstring` | `0x1328` | `0x1368` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x10c0` | `0x10e0` | **`+0x20`** |
| `__DATA.__data` | `0x720` | `0x730` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x870` | `0x880` | **`+0x10`** |
| `__TEXT.__const` | `0xb20` | `0xb30` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x708` | `0x718` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3232.3.0.0.0
+3234.5.0.0.0

-  Symbols:   266
-  CStrings:  418
+  Symbols:   267
+  CStrings:  419
Symbols:
+ _swift_retain_x27
Functions:
~ sub_29e8 : 264 -> 72
~ sub_2af0 -> sub_2a30 : 156 -> 100
~ sub_2b8c -> sub_2a94 : 140 -> 84
~ sub_2c18 -> sub_2ae8 : 152 -> 96
~ sub_ec3c -> sub_ead4 : 5248 -> 6020
~ sub_24b2c -> sub_24cc8 : 196 -> 140
~ sub_24d3c -> sub_24ea0 : 344 -> 216
~ sub_25c90 -> sub_25d74 : 824 -> 816
~ sub_25fc8 -> sub_260a4 : 804 -> 796
~ sub_26654 -> sub_26728 : 616 -> 576
~ sub_268bc -> sub_26968 : 616 -> 576
CStrings:
+ "Not caching availability for %s: error=%s timedOut=%{bool}d"
```
