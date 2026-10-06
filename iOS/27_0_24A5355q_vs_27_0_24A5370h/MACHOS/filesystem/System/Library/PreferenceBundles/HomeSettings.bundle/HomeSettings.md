## HomeSettings

> `/System/Library/PreferenceBundles/HomeSettings.bundle/HomeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59d4` | `0x5aa8` | **`+0xd4`** |
| `__TEXT.__objc_methname` | `0x2ae6` | `0x2b38` | **`+0x52`** |
| `__DATA_CONST.__cfstring` | `0x11e0` | `0x1220` | **`+0x40`** |
| `__TEXT.__cstring` | `0xfd8` | `0x1010` | **`+0x38`** |
| `__TEXT.__objc_stubs` | `0x1880` | `0x18a0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x428` | `0x440` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xc20` | `0xc30` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1216.4.0.1.11
+1227.0.0.0.1

-  Symbols:   213
-  CStrings:  659
+  Symbols:   216
+  CStrings:  663
Symbols:
+ OBJC_IVAR_$_PSSpecifier.keyboardType
+ _HFMaxConcurrentLiveStreamsKey
+ _HFShouldCapConcurrentLiveStreamsKey
Functions:
~ sub_2130 : 352 -> 348
~ sub_2290 -> sub_228c : 320 -> 316
~ sub_4d70 -> sub_4d68 : 5536 -> 5732
~ sub_63d4 -> sub_6490 : 132 -> 160
~ sub_67f0 -> sub_68c8 : 380 -> 376
CStrings:
+ "Cap Concurrent Live Streams"
+ "Max Concurrent Live Streams"
+ "setClearButtonMode:"
+ "setKillHomeForSpecifierValueAndReloadAllSpecifiers:specifier:"
```
