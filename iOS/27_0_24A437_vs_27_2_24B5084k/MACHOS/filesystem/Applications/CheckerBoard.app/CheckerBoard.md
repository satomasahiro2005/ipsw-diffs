## CheckerBoard

> `/Applications/CheckerBoard.app/CheckerBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0xca00` | `0xc940` | **`-0xc0`** |
| `__TEXT.__text` | `0x69408` | `0x69378` | **`-0x90`** |
| `__TEXT.__objc_methname` | `0x11e11` | `0x11d91` | **`-0x80`** |
| `__DATA.__objc_selrefs` | `0x4378` | `0x4348` | **`-0x30`** |
| `__DATA_CONST.__got` | `0xb48` | `0xb40` | **`-0x8`** |

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

-294.0.6.0.0
+294.40.3.0.0

-  Symbols:   1032
-  CStrings:  4417
+  Symbols:   1031
+  CStrings:  4411
Symbols:
- _OBJC_CLASS_$_FBSDeviceEmulationConfiguration
Functions:
~ sub_100008be8 : 12 -> 16
~ sub_100008bf4 -> sub_100008bf8 : 16 -> 12
~ sub_10003b67c : 96 -> 64
~ sub_10003b6dc -> sub_10003b6bc : 96 -> 64
~ sub_10003b7dc -> sub_10003b79c : 152 -> 148
~ sub_10003b874 -> sub_10003b830 : 92 -> 48
~ sub_100069158 -> sub_1000690e8 : 124 -> 92
CStrings:
- "emulatedArtworkSubtype"
- "emulatedDeviceClass"
- "emulatedDisplayCornerRadius"
- "emulatedHomeButtonType"
- "hasEmulatedDeviceBounds"
- "isEmulatedDevice"
```
