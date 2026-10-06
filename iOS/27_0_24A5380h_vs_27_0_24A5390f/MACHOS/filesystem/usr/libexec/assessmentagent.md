## assessmentagent

> `/usr/libexec/assessmentagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x961a4` | `0x96250` | **`+0xac`** |
| `__TEXT.__swift5_reflstr` | `0x372d` | `0x379d` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x3699` | `0x36c9` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x79c0` | `0x79e8` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x3238` | `0x325c` | **`+0x24`** |
| `__TEXT.__cstring` | `0x1c18` | `0x1c38` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2420` | `0x2440` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xa88` | `0xa90` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x878` | `0x880` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-55.0.0.0.0
+56.0.0.0.0

-  Symbols:   945
-  CStrings:  1079
+  Symbols:   946
+  CStrings:  1081
Symbols:
+ _MCFeatureAutoCapitalizationAllowed
Functions:
~ sub_10001b1f0 : 916 -> 936
~ sub_1000596e4 -> sub_1000596f8 : 2864 -> 2876
~ sub_10006bb98 -> sub_10006bbb8 : 336 -> 368
~ sub_10006bce8 -> sub_10006bd28 : 40 -> 44
~ sub_10006f128 -> sub_10006f16c : 1872 -> 1920
~ sub_100092a04 -> sub_100092a78 : 2652 -> 2708
CStrings:
+ "allowsAccessibilityFullKeyboardAccess"
+ "fullKeyboardAccess"
```
