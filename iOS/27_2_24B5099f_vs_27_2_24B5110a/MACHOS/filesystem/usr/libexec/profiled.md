## profiled

> `/usr/libexec/profiled`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc9784` | `0xc97f8` | **`+0x74`** |
| `__DATA_CONST.__cfstring` | `0x8700` | `0x8740` | **`+0x40`** |
| `__TEXT.__cstring` | `0xaa0a` | `0xaa4a` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x2a00` | `0x2a20` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x16c17` | `0x16c37` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x13480` | `0x134a0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1510` | `0x1520` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x54d8` | `0x54e0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2148` | `0x2150` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   1816
-  CStrings:  5779
+  Symbols:   1819
+  CStrings:  5782
Symbols:
+ _MCFeaturePairingWithHomeDevicesAllowed
+ _MCGestaltIsHomeAccessory
+ _MCLocalizedStringInTable
Functions:
~ sub_10001faa0 : 12 -> 80
~ sub_1000204a4 -> sub_1000204e8 : 12 -> 20
~ sub_100043674 -> sub_1000436c0 : 1092 -> 1116
~ sub_100047658 -> sub_1000476bc : 336 -> 352
CStrings:
+ "INSTALL_PAIRED_COMPANION_CHOOSE_ACCESSORIES"
+ "Localizable-J490"
+ "areAnyHomeAccessoriesConfigured"
+ "restriction_allowPairingWithHomeDevices"
- "INSTALL_PAIRED_COMPANION_HOMEPOD"
```
