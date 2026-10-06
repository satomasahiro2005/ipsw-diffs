## MobileCalSettings

> `/System/Library/PreferenceBundles/MobileCalSettings.bundle/MobileCalSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x1487` | `0x1567` | **`+0xe0`** |
| `__DATA_CONST.__cfstring` | `0x11c0` | `0x1200` | **`+0x40`** |
| `__TEXT.__text` | `0x1003c` | `0x10078` | **`+0x3c`** |
| `__TEXT.__objc_stubs` | `0x2b40` | `0x2b20` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x4184` | `0x416f` | **`-0x15`** |
| `__DATA.__objc_selrefs` | `0x10b0` | `0x10a8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-29902.0.100.0.0
+29906.0.0.0.0

-  CStrings:  944
+  CStrings:  945
Functions:
~ sub_362c : 296 -> 292
~ sub_5ed0 -> sub_5ecc : 548 -> 544
~ sub_7214 -> sub_720c : 2136 -> 2236
~ sub_7a6c -> sub_7ac8 : 400 -> 396
~ sub_7cc4 -> sub_7d1c : 92 -> 96
~ sub_8e28 -> sub_8e84 : 508 -> 504
~ sub_91ac -> sub_9204 : 436 -> 432
~ sub_a990 -> sub_a9e4 : 524 -> 520
~ sub_ad4c -> sub_ad9c : 544 -> 540
~ sub_bd48 -> sub_bd94 : 616 -> 612
~ sub_d5c8 -> sub_d610 : 540 -> 536
~ sub_f6d4 -> sub_f718 : 2992 -> 2996
~ sub_116e8 -> sub_11730 : 376 -> 364
CStrings:
+ "Smart Event Details requires a language supported by Apple Intelligence. You can change this in Language & Region settings."
+ "Smart Event Details requires the Gregorian calendar. You can change this in Language & Region settings."
+ "magicComposeSettingsAvailability"
- "isAppleIntelligenceEnabled"
- "isMagicComposeAllowedByMDM"
```
