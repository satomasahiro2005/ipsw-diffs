## CheckerBoard

> `/Applications/CheckerBoard.app/CheckerBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0xcaa0` | `0xcb60` | **`+0xc0`** |
| `__TEXT.__text` | `0x69a34` | `0x69ac4` | **`+0x90`** |
| `__TEXT.__objc_methname` | `0x11f81` | `0x12001` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x43b0` | `0x43e0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xb68` | `0xb70` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   1036
-  CStrings:  4435
+  Symbols:   1037
+  CStrings:  4441
Symbols:
+ _OBJC_CLASS_$_FBSDeviceEmulationConfiguration
Functions:
~ sub_100008ca0 : 16 -> 12
~ sub_100008cb0 -> sub_100008cac : 12 -> 16
~ sub_10003bb3c : 64 -> 96
~ sub_10003bb7c -> sub_10003bb9c : 64 -> 96
~ sub_10003bc5c -> sub_10003bc9c : 148 -> 152
~ sub_10003bcf0 -> sub_10003bd34 : 48 -> 92
~ sub_10006985c -> sub_1000698cc : 92 -> 124
CStrings:
+ "emulatedArtworkSubtype"
+ "emulatedDeviceClass"
+ "emulatedDisplayCornerRadius"
+ "emulatedHomeButtonType"
+ "hasEmulatedDeviceBounds"
+ "isEmulatedDevice"
```
