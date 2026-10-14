## AirPlayAndHandoffSettings

> `/System/Library/PreferenceBundles/AirPlayAndHandoffSettings.bundle/AirPlayAndHandoffSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10a28` | `0x10c38` | **`+0x210`** |
| `__TEXT.__cstring` | `0xa1c` | `0xa7c` | **`+0x60`** |
| `__DATA.__data` | `0x8f0` | `0x910` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x418` | `0x430` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x310` | `0x318` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.1.1.0.0
+2027.1.1.101.0

-  Functions: 328
+  Functions: 331

-  CStrings:  70
+  CStrings:  72
Symbols:
+ _objc_retain_x25
+ _swift_retain_x20
- _objc_retain_x23
- _swift_retain_x28
CStrings:
+ "Handoff to Home Devices"
+ "HomeDevices-J490"
+ "Primary text, toggle. 'Handoff' is an Apple feature name."
- "Transfer to HomePod"
```
