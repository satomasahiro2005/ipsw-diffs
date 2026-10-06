## CarPlaySettings

> `/Applications/CarPlaySettings.app/CarPlaySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd94d8` | `0xd96f4` | **`+0x21c`** |
| `__TEXT.__swift5_typeref` | `0xfa98` | `0xfb48` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x4124` | `0x4164` | **`+0x40`** |
| `__DATA.__data` | `0x5078` | `0x5098` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x3500` | `0x3520` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xc18` | `0xc24` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xf90` | `0xf98` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-580.0.0.0.0
+581.7.1.0.0

-  CStrings:  4217
+  CStrings:  4219
Symbols:
+ _AFIsLinwoodEnabledAndWasEverAvailable
- _AFIsLinwoodEnabledAndAvailable
Functions:
~ sub_10001c940 : 484 -> 508
~ sub_100065254 -> sub_10006526c : 3084 -> 3332
~ sub_1000a1abc -> sub_1000a1bcc : 3484 -> 3752
CStrings:
+ "AmbientLightSyncToggle"
+ "com.apple.application-icon.siri"
```
